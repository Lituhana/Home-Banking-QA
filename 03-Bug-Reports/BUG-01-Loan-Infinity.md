# 🐛 BUG-01: Missing Validation for Maximum Loan Amount

**Severity:** - Major  
**Priority:** - High  
**Status:** - Open  

## 📝 Description:
The "Loan Amount" input field does not validate the maximum allowed value. The system permits users to request astronomical amounts (e.g., $999,999,999,999), causing the account balance to display "Infinity" and breaking the UI logic.

## 👣 Steps to Reproduce:
1. Log in to the application.
2. Navigate to the **Loans** section.
3. Enter `999999999999` in the amount field.
4. Click on the "Request Loan" button.

## ✅ Expected Result:
The application should display a validation message: "The requested amount exceeds the maximum allowed limit."

## ❌ Actual Result:
The loan is approved instantly, and the total balance is updated to "Infinity".