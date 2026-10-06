# Demoblaze E-Commerce QA Testing Suite

A comprehensive **Manual Testing / Software Testing portfolio project** for the [Demoblaze](https://www.demoblaze.com/) e-commerce web application.

This project demonstrates practical QA activities including test planning, requirements traceability, test case design, test execution, defect reporting, and summary analysis.

## Project Overview

**Application Under Test:** Demoblaze Web Application  
**Application URL:** https://www.demoblaze.com/  
**Testing Type:** Manual / Functional Testing  
**Project Version:** 3.0  
**Project Date:** October 2026  
**QA Lead / Author:** Shravani Salunkhe

## Project Scope

The testing suite covers the major functional areas of the Demoblaze application:

- Navigation
- User Registration
- User Login / Logout
- Product Catalog
- Product Categories
- Shopping Cart
- Checkout / Place Order
- Contact functionality
- About Us modal
- Basic validation and negative scenarios

## Test Artifacts

The main Excel workbook contains the following sheets:

| Sheet | Purpose |
|---|---|
| **Dashboard & Summary** | Overall QA metrics, module-wise coverage, and execution results |
| **Test_Plan** | Testing objectives, scope, approach, resources, risks, and schedule |
| **Requirements_RTM** | Requirement Traceability Matrix mapping requirements to test cases |
| **Test_Cases** | Detailed functional test cases with steps, data, and expected results |
| **Test_Execution** | Execution status and execution notes for test cases |
| **Defect_Log** | Defects identified during testing with severity, priority, reproduction steps, and expected/actual results |

## Test Coverage

The workbook contains:

- **6 requirements**
- **28 test cases**
- **28 executed test cases**
- **23 passed test cases**
- **5 failed test cases**
- Multiple documented defects across authentication, cart, checkout, and catalog functionality

## Key Defects Identified

Examples of defects documented in the defect log include:

1. Purchase order can be completed without mandatory Name and Credit Card information.
2. Registration allows invalid/empty credential submission without appropriate local validation.
3. Cart total does not dynamically recalculate after deleting an item.
4. Place Order modal may display an incorrect total immediately after item deletion.
5. Promotional banner carousel controls may freeze intermittently during rapid interaction.

See the **Defect_Log** sheet for complete reproduction steps, severity, priority, status, and expected vs. actual results.


## Screenshots & Visual Evidence

screenshots/
|--test_execution/                 #Evidence of successful test run (PASS)
|--defect_evidence/                #Evidence of discovered bug/defects (FAIL)

## Testing Approach

The project follows a structured manual testing workflow:

1. Understand application requirements.
2. Define test scope and test objectives.
3. Prepare the Test Plan.
4. Identify requirements and create the RTM.
5. Design positive and negative test cases.
6. Execute test cases against the application.
7. Record PASS / FAIL results.
8. Log defects with clear reproduction steps.
9. Analyze test results.
10. Prepare the final QA summary.


## How to Use This Project

1. Open the Excel workbook.
2. Start with **Dashboard & Summary** for the overall project status.
3. Review **Test_Plan** to understand the testing strategy.
4. Review **Requirements_RTM** to understand requirement-to-test coverage.
5. Open **Test_Cases** to review detailed test scenarios.
6. Check **Test_Execution** for execution results.
7. Review **Defect_Log** for identified bugs.

## Skills Demonstrated

This project demonstrates practical knowledge of:

- Manual Software Testing
- Functional Testing
- Positive & Negative Testing
- Test Case Design
- Test Planning
- Requirement Traceability Matrix (RTM)
- Test Execution
- Defect / Bug Reporting
- Severity and Priority Classification
- Regression Testing Concepts
- QA Documentation
- Excel-based Test Management
- E-commerce Application Testing

## Future Improvements

The project can be extended with:

- Selenium / Playwright automation
- API testing
- SQL/database validation
- Cross-browser testing
- Mobile/responsive testing
- Performance testing
- CI/CD integration
- Automated HTML test reports

## Disclaimer

This is a QA portfolio/testing project created for educational and demonstration purposes. The Demoblaze application is an external demo website, and this repository is not affiliated with or endorsed by Demoblaze.

## Author

**Shravani Salunkhe**  
QA / Software Testing Portfolio

If you find this project useful, feel free to ⭐ the repository.
