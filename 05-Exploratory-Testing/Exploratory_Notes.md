# 📝 Exploratory Testing Notes

**Date:** 09-02-2026  
**Focus:** UI/UX, Boundary Value Analysis, Responsiveness and Session Stability.


## ⚒️ Areas Covered

- Balance Integrity: Verified that requesting loans and making transfers correctly updates the total balance in real time.

- Input Validation: Tested fields with special characters and out of range numbers (ex. Loans over $500.000), the system correctly blocked these actions.

- UI/UX Analysis: Checked for consistency between the Dashboard and specific modules (Transfers, cards and loans).

- State Management: Investigated how the application handles data removal interactions.


## 💡 Observations and Findings

- Product Clarification: Confirmed that the "Tarjeta de Crédito" shown in the Dashboard is a separate entity from the "Tarjetas Virtuales" section.

- **UI Issue [(BUG-DASH-01)](https://github.com/Lituhana/Home-Banking-QA-Project/blob/main/04-Evidence/Screenshots%20%26%20Videos/BUGS/BUG-DASH-01.png):** Identified a lack of responsiveness in the Dashboard and other sections when resizing the window.

- **Critical Issue [(BUG-LOAN-02)](https://github.com/Lituhana/Home-Banking-QA-Project/blob/main/04-Evidence/Screenshots%20%26%20Videos/BUGS/BUG-LOAN-02.mp4):** Discovered a major stability flaw, cancelling the oldest fixed term triggers a total UI deadlock, this is a critical bug since it leaves the user unable to navigate or log out.


### 🚀 Conclusion


While the basic business rules (like loan limits and balance updates) work as intended, the application has significant stability and UI issues. The freezing found during data removal (BUG-LOAN-02) and the responsiveness flaws (BUG-DASH-01) need to be addressed.
