# 📝 Exploratory Testing Notes

**Date:** 09-02-2026  
**Focus:** UI/UX, Boundary Value Analysis and Responsiveness.


📝 Areas Covered:

    Balance Integrity: Verified that requesting loans and making transfers correctly updates the total balance in real-time.

    Input Validation: Tested fields with special characters and out-of-range numbers (e.g. loans over $500,000). The system correctly blocked these actions.

    UI/UX Analysis: Checked for consistency between the Dashboard and specific modules (Transfers, Cards and Loans).

💡 Observations and Findings:

    Positive Finding: The "Restablecer saldos" feature works perfectly and is a great tool for maintaining a clean test environment.

    Product Clarification: Confirmed that the "Tarjeta de Crédito" shown in the Dashboard is a separate entity from the "Tarjetas Virtuales" section, which requires manual generation.

    Navigation: The menu flow is intuitive and the session remains stable across different sections.

🚀 Conclusion:

The core functionalities are stable and follow the business rules. Except for the responsiveness issue reported in BUG-01, the application provides a smooth user experience.