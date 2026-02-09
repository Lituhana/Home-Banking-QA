# 📝 Exploratory Testing Notes

**Session Date:** 09-02-2026  
**Focus:** UI/UX, Boundary Value Analysis, and Mobile Responsiveness.

## 🔍 Findings and Observations:

- **Input Overflows (Transfers):** The CBU field allows entering more than 22 characters without any visual warning or `maxlength` restriction. This could lead to malformed data sent to the server.
- **Responsive Issues:** When inspecting the dashboard using "Mobile View" (iPhone SE/Pixel 7), the sidebar navigation menu overlaps with the "Recent Transactions" header, making it difficult to read.
- **Visual Consistency:** In the "Virtual Cards" section, the loading spinner is slightly off-center inside the button during the generation process.
- **Security/Session:** Verified that the session remains active even after refreshing the page multiple times (F5), which is correct for the current scope.

## 💡 Recommendations:
- Implement a 22-character limit on the CBU input.
- Fix CSS media queries for resolutions under 400px.
- Add backend validation for maximum loan amounts to prevent "Infinity" balance errors.