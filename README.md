# ecommerce-manual-testing-project
Manual Testing project for an E-Commerce web application using Microsoft Excel.
# E-Commerce Manual Testing Project

## Project Overview

This project demonstrates a complete Manual Testing process for an E-Commerce web application.

The project covers test planning, test scenario creation, test case design, test execution, defect reporting, requirement traceability, and test summary reporting.

The application used for practice is SauceDemo, a demo e-commerce website designed for software testing practice.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Project Objective

The main objective of this project is to verify that the major functionalities of the E-Commerce application work as expected and to identify, document, and track defects.

### Key objectives

* Verify application functionality.
* Validate user input and error messages.
* Test positive and negative scenarios.
* Verify the shopping workflow.
* Identify and document defects.
* Maintain requirement-to-test-case traceability.
* Execute and document test cases.
* Prepare a final test summary report.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Application Under Test

Application: SauceDemo

URL: https://www.saucedemo.com/

Application Type: Web Application

Testing Type: Manual Testing

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Test Credentials

For the standard user test account:

```text
Username: standard_user
Password: secret_sauce

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Testing Scope

The following modules are covered:

* Login
* User Authentication
* Product Listing
* Product Details
* Product Search
* Shopping Cart
* Checkout
* Order Processing
* Navigation
* UI Validation
* Negative Testing

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Testing Types

The following testing techniques and types were considered:

* Functional Testing
* Smoke Testing
* Sanity Testing
* Regression Testing
* Retesting
* UI Testing
* Negative Testing
* Exploratory Testing
* Boundary Value Analysis
* Equivalence Partitioning

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Tools Used

| Tool            | Purpose                                                    |
| --------------- | ---------------------------------------------------------- |
| Microsoft Excel | Test cases, test scenarios, RTM, bug reports and execution |
| Google Chrome   | Web application testing                                    |
| Chrome DevTools | Basic browser inspection and debugging                     |
| GitHub          | Project documentation and version control                  |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Project Structure

```text
ecommerce-manual-testing-project/
│
├── README.md
│
├── 01_Test_Plan/
│   └── Test_Plan.xlsx
│
├── 02_Test_Scenarios/
│   └── Test_Scenarios.xlsx
│
├── 03_Test_Cases/
│   └── Test_Cases.xlsx
│
├── 04_Bug_Reports/
│   └── Bug_Reports.xlsx
│
├── 05_RTM/
│   └── RTM.xlsx
│
├── 06_Test_Execution/
│   └── Test_Execution.xlsx
│
├── 07_Test_Summary/
│   └── Test_Summary_Report.pdf
│
└── Screenshots/
    ├── Login/
    ├── Product/
    ├── Cart/
    ├── Checkout/
    └── Bugs/

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Test Documentation

### 1. Test Plan

The Test Plan defines the testing objectives, scope, testing types, environment, entry criteria, exit criteria, risks, and deliverables.

File: `01_Test_Plan/Test_Plan.xlsx`

### 2. Test Scenarios

High-level scenarios were created to identify the functionalities that need to be tested.

File: `02_Test_Scenarios/Test_Scenarios.xlsx`

### 3. Test Cases

Detailed test cases were created with test steps, test data, expected results, actual results, status, and bug IDs.

File: `03_Test_Cases/Test_Cases.xlsx`

### 4. Bug Reports

Defects identified during test execution are documented with steps to reproduce, expected result, actual result, severity, priority, and status.

File: `04_Bug_Reports/Bug_Reports.xlsx`

### 5. Requirement Traceability Matrix

The RTM maps requirements to corresponding test cases to ensure complete test coverage.

File: `05_RTM/RTM.xlsx`

### 6. Test Execution

Test execution results are recorded as Pass, Fail, Blocked, or Not Executed.

File: `06_Test_Execution/Test_Execution.xlsx`

### 7. Test Summary Report

The final report summarizes the testing activities, execution results, defects, limitations, and overall testing conclusion.

File: `07_Test_Summary/Test_Summary_Report.pdf`

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Testing Process

The following testing workflow was followed:

```text
Requirement Analysis
        ↓
Test Planning
        ↓
Test Scenario Creation
        ↓
Test Case Design
        ↓
Test Data Preparation
        ↓
Test Execution
        ↓
Defect Identification
        ↓
Bug Reporting
        ↓
Retesting
        ↓
Regression Testing
        ↓
Test Summary

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Defect Management

When a test case fails, a defect is documented with:

* Bug ID
* Test Case ID
* Bug Title
* Module
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Environment
* Status
* Screenshot

### Defect Severity

| Severity | Description                                                      |
| -------- | ---------------------------------------------------------------- |
| Critical | Critical functionality is unavailable or application is unusable |
| High     | Major functionality is not working                               |
| Medium   | Functionality is partially affected                              |
| Low      | Minor UI or cosmetic issue                                       |

### Defect Priority

| Priority | Description                            |
| -------- | -------------------------------------- |
| High     | Should be fixed immediately            |
| Medium   | Should be fixed in the current release |
| Low      | Can be fixed in a future release       |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Test Execution Status

The final execution numbers should be updated after completing actual testing.

| Metric           | Result |
| ---------------- | -----: |
| Total Test Cases |     50 |
| Executed         |    TBD |
| Passed           |    TBD |
| Failed           |    TBD |
| Blocked          |    TBD |
| Not Executed     |    TBD |
| Total Defects    |    TBD |

> Note: Test results and defect counts are updated based on actual execution. No test result is considered Pass or Fail until the corresponding test case has been executed.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Screenshots

Screenshots are included as evidence of test execution and defects.

Examples:

```text
Screenshots/
├── Login/
│   ├── TC_006_Login_Success.png
│   └── TC_008_Invalid_Login.png
│
├── Product/
│   └── TC_012_Product_List.png
│
├── Cart/
│   ├── TC_022_Add_To_Cart.png
│   └── TC_027_Cart_Total.png
│
├── Checkout/
│   └── TC_028_Checkout.png
│
└── Bugs/
    ├── BUG_001.png
    └── BUG_002.png

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Tester

Name: Neha Bihade

Role: Manual Testing / QA

Skills Demonstrated:

* Manual Testing
* Test Case Design
* Test Scenario Design
* Functional Testing
* Regression Testing
* Smoke Testing
* Sanity Testing
* Retesting
* Bug Reporting
* RTM
* Test Execution
* Microsoft Excel
* Chrome DevTools
* GitHub

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Key Learning

Through this project, I practiced the complete Software Testing Life Cycle (STLC), including requirement analysis, test planning, test design, test execution, defect reporting, retesting, regression testing, and test closure.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Disclaimer

This is a practice/portfolio testing project created for learning and demonstrating Manual Testing skills.

The application under test is a publicly available demo application. Test results and defects are based only on actual test execution performed during the project.
