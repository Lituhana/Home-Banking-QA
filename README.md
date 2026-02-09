# **MANUAL QA TESTING PROJECT** for a Home Banking Demo Application 💻


This repository contains a manual QA testing project for a Home Banking demo web application (version 3.0).  
The goal of this project is to practice and demonstrate core manual QA skills, including test case design, test execution, bug reporting and evidence collection, following a basic real world manual testing workflow.



## 🧪 Test Environment

- Application: Home Banking Demo Web Application v3.0
- Environment: Demo / Testing
- Browsers: Google Chrome
- Testing Type: Manual and exploratory testing



## 📂 Project Structure:

- **`01-Documentation`** → Functional specifications and test related documentation.
    - [Functional Specifications - Google Doc](https://docs.google.com/document/d/1KcJmUn0KpLSNQxVGpXlYsOVFYvabJrrsrYG_KFsHDq4/edit?tab=t.0)  
    - [Test Plan - Google Doc](https://docs.google.com/document/d/1mw2tHUOUtaQeuTKEvuixQkx5sPYfQTgVr5d5Hxb17q8/edit?tab=t.0)
- **`02-Tests`** → Executed manual test cases.
- **`03-Bug-Reports`** → Bug reports created from failed test executions.
- **`04-Evidence`** → Screenshots and videos as test evidence.
- **`05-Exploratory-Testing`** → Notes from exploratory testing sessions.
- `README.md`


------------------------------------------------------------------------------------------------------------------------------

### 🔐 Authentication Test Cases:

- **This section covers positive and negative authentication tests, focusing on access control and session handling**

The following test cases are included:

- Successful login with valid credentials
- Login attempt with invalid credentials
- Account lockout 
- Successful logout
- Documentation panel on the login screen

The test cases for the authentication part are located in:

- [Authentication Test Cases - on GitHub](02-Test-Cases/Authentication-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=0#gid=0)


-------------------------------------------------------------------------------------------------------------------------------

### 🏦 Dashboard Test Cases:

- **This section focuses on validating the main dashboard functionalities**

The following test cases are included:

- Product visualization
- Recent transactions
- Balance reset

The test cases for the dashboard part are located in:

- [Dashboard Test Cases - on GitHub](02-Test-Cases/Dashboard-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=930553732#gid=930553732)


------------------------------------------------------------------------------------------------------------------------------

### 💵 Loan Test Cases

- **This section focuses on validating the loan management functionality, including creation, validation rules, cancellation and early withdrawal test cases**

The following test cases are included:

- Successful loan request
- Maximum loan amount validation
- Full loan repayment
- Early loan withdrawal availability 
- Successful early withdrawal without interest
- Early withdrawal with insufficient balance

The test cases for the loan part are located in:

- [Loan Test Cases - on GitHub](02-Test-Cases/Loan-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=1705885976#gid=1705885976)


------------------------------------------------------------------------------------------------------------------------------

### 🔁 Transfer Test Cases

- **This section validates money movement between accounts, ensuring that business rules like transaction limits and CBU validation are working properly**

The following test cases are included:

- Successful transfer between own accounts 
- Single operation amount limit validation
- Daily transfer limit validation 
- Invalid CBU length validation

The test cases for the transfer part are located in:

- [Transfer Test Cases - on GitHub](02-Test-Cases/Transfer-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=818843615#gid=818843615)


------------------------------------------------------------------------------------------------------------------------------

### ⌛ Fixed Term Deposits Test Cases

- **This section focuses on the creation of fixed term deposits and the accurate calculation of interest rates and maturity dates**

The following test cases are included:

- Fixed term deposit constitution and interest calculation
- Minimum investment amount validation
- Maximum simultaneous active deposits limit

The test cases for the fixed term deposit part are located in:

- [Fixed Term Deposits Test Cases - on GitHub](02-Test-Cases/Fixed-Term-Deposits-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=73838471#gid=73838471)


------------------------------------------------------------------------------------------------------------------------------

### 🧾 Service Payment Test Cases

- **This section covers the workflow for paying utility bills and services, validating balance checks and receipt generation**

The following test cases are included:

- Successful service payment and PDF receipt generation.
- Insufficient balance validation for service payments.

The test cases for the service payment part are located in:

- [Service Payment Test Cases - on GitHub](02-Test-Cases/Service-Payment-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=430665678#gid=430665678)


------------------------------------------------------------------------------------------------------------------------------

### 💳 Virtual Card Test Cases

- **This part of the project covers the creation of virtual cards, focusing on generation rules and UI/UX consistency**

The following test cases are included:

- Virtual card generation limit.
- Verification of card deletion and regeneration 
- Visual testing: - Loading spinners and card layout

The test cases for the virtual card part are located in:

- [Virtual Card Test Cases - on GitHub](02-Test-Cases/Virtual-Card-Test-Cases.xlsx)
- [Google Sheet / Excel version](https://docs.google.com/spreadsheets/d/1t88yE43r9wVuuUoNFoY1y9TbTT7ObUUGuqvRaaaL9FQ/edit?gid=424030347#gid=424030347)


------------------------------------------------------------------------------------------------------------------------------

## 📊 Test Execution Summary

| Module | Test Cases | Passed | Failed | Status |
| :--- | :---: | :---: | :---: | :--- |
| Authentication | 5 | 5 | 0 | ✅ Passed |
| Dashboard | 3 | 3 | 0 | ✅ Passed |
| Loans | 6 | 6 | 0 | ✅ Passed |
| Transfers | 4 | 4 | 0 | ✅ Passed |
| Fixed Term | 3 | 3 | 0 | ✅ Passed |
| Service Payments | 2 | 2 | 0 | ✅ Passed |
| Virtual Cards | 3 | 3 | 0 | ✅ Passed |
  
  
**Total Execution Rate: 100% | Success Rate: 100%**

------------------------------------------------------------------------------------------------------------------------------

## 🖥️ Project Status and Next Steps

During this testing cycle, I verified the core functionalities of the application, including login, dashboard, transfers, loans, fixed term deposits, service payments and virtual cards. As today 09/02/2026 with the version 3.0 the home banking is working as expected based on the predefined test cases.

As a next step, I will be performing Exploratory Testing to identify any potential edge cases, hidden bugs, or UI/UX inconsistencies that weren't covered in the initial documentation.