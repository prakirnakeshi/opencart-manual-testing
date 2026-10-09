# OpenCart Manual Testing Project

A practical Manual QA Testing project focused on validating the functionality of an e-commerce application using structured test scenarios and test cases.

This project demonstrates an understanding of manual testing fundamentals, the Software Testing Life Cycle (STLC), positive and negative testing, test case design, test execution tracking, and test traceability.

---

## 📌 Project Overview

| Attribute | Details |
|---|---|
| Project Name | OpenCart Manual Testing |
| Application Under Test | OpenCart E-Commerce Application |
| Testing Type | Manual Testing |
| Testing Approach | Functional and Scenario-Based Testing |
| Total Test Cases | 50 |
| Modules Covered | 11 |
| Happy Path Test Cases | 37 |
| Negative Test Cases | 13 |
| Test Documentation | Microsoft Excel |
| Test Plan | PDF and Word |
| Version Control | Git and GitHub |

---

## 🎯 Project Objectives

The primary objectives of this project are:

- Understand the functional workflows of an e-commerce application.
- Identify important application modules and test scenarios.
- Design clear, structured, and reusable manual test cases.
- Cover positive and negative testing conditions.
- Define preconditions, test data, test steps, and expected results.
- Organize test documentation professionally.
- Maintain traceability between test scenarios and test cases.
- Support test execution tracking and actual-result recording.
- Apply fundamental software testing concepts to a practical application.
- Build a structured QA portfolio demonstrating manual testing skills.

---

## 🏗️ Application Under Test

The application under test is the OpenCart e-commerce application.

The project focuses on validating common e-commerce workflows, including:

- Homepage and navigation
- Currency selection
- User registration
- Login and authentication
- Product browsing and search
- Wishlist and product comparison
- Shopping cart operations
- Checkout
- Customer account management
- Payment and order placement

The objective is to evaluate application behavior under normal usage conditions and selected negative test conditions.

**Application:** [OpenCart Demo Website](https://demo.opencart.com/)

*Note: The application is a publicly accessible demo. Its availability, configuration, data, and functionality may change over time.*

---

## 🧪 Master Test Cases — Preview

The following table provides a quick overview of representative test cases from the project.

These examples demonstrate how the test suite covers essential e-commerce workflows, including registration, authentication, wishlist management, shopping cart operations, checkout, and product search.

| Test Case ID | Module | Test Case Title | Test Type |
|---|---|---|---|
| M01-S01-TC01 | Homepage & Featured Products | Verify homepage is displayed correctly | Happy Path |
| M02-S01-TC01 | Header & Navigation | Verify Header Elements and My Account Navigation Menu | Happy Path |
| M03-S03-TC01 | Currency | Verify Product Prices Update After Changing Currency | Happy Path |
| M04-S01-TC01 | User Registration | Register with Valid Mandatory Details | Happy Path |
| M04-S02-TC01 | User Registration | Verify Registration with Invalid Email Format | Negative |
| M05-S01-TC01 | Login & Authentication | Login with Valid Registered Credentials | Happy Path |
| M05-S02-TC01 | Login & Authentication | Login with a valid username/email and invalid password | Negative |
| M06-S02-TC01 | Wishlist & Product Compare | Add a Product to Wishlist While Logged Out | Negative |
| M07-S03-TC01 | Shopping Cart | Verify Updating Product Quantity in the Shopping Cart | Happy Path |
| M08-S01-TC01 | Checkout | Verify Proceeding to Checkout with a Valid Cart | Happy Path |
| M08-S03-TC01 | Checkout | Verify Checkout Behavior with an Empty Shopping Cart | Negative |
| M09-S01-TC01 | Product Search | Verify Product Search Using an Exact Product Name | Happy Path |

The table is intended as a preview rather than a replacement for the complete test suite.

### 📥 Complete Test Case Documentation

The full Excel workbook contains detailed test cases, preconditions, test data, test steps, expected results, and supporting QA documentation.

**[Download the Complete OpenCart QA Test Cases](Test-Documentation/OpenCart_QA_Test_Cases.xlsx)**

The workbook consolidates the detailed documentation into a single file, making it easier to review the complete test suite.

---

## 🧪 Testing Scope

The project covers the following 11 modules.

### 1. Homepage & Featured Products

Testing includes:

- Homepage display and loading
- Featured product visibility
- Homepage carousel and banner behavior
- Featured product links
- Basic homepage functionality

### 2. Header & Navigation

Testing includes:

- Header elements
- Navigation menu visibility
- My Account navigation
- Wishlist navigation
- Shopping cart navigation
- Checkout navigation
- Logo navigation to the homepage

### 3. Currency

Testing includes:

- Default currency display
- Available currency options
- Currency selection
- Product price updates after changing currency
- Cart price updates after changing currency
- Currency persistence during navigation

### 4. User Registration

Testing includes:

- Registration with valid mandatory details
- Invalid email format
- Password length validation
- Password confirmation
- Required terms and conditions
- Registration form validation

### 5. Login & Authentication

Testing includes:

- Login with valid credentials
- Login with an invalid password
- Login using an unregistered email or username
- Submission with blank login fields
- Password masking
- Authentication-related validation

### 6. Wishlist & Product Compare

Testing includes:

- Adding a product to the wishlist while logged in
- Adding a product to the wishlist while logged out
- Removing a product from the wishlist
- Adding products to comparison
- Verifying product comparison functionality

### 7. Shopping Cart

Testing includes:

- Adding a single product to the cart
- Adding multiple products
- Updating product quantity
- Removing products
- Validating cart subtotal and total
- Retaining cart contents during navigation

### 8. Checkout

Testing includes:

- Proceeding to checkout with a valid cart
- Entering valid billing and shipping information
- Checkout behavior with an empty cart
- Validating the checkout workflow

### 9. Product Search

Testing includes:

- Searching using an exact product name
- Searching using a partial product name
- Searching with different letter cases
- Searching with no input
- Searching with leading and trailing spaces
- Handling searches with no matching results

### 10. My Account

Testing includes:

- Viewing the account dashboard after login
- Adding or updating a valid address
- Changing a password using valid information

### 11. Payment & Order Placement

Testing includes:

- Selecting an available payment method
- Completing an order using a supported payment flow
- Verifying order confirmation after successful placement

The Excel workbook provides the detailed test steps and expected results for the documented test cases.

---

## 📊 Test Coverage

The project contains 50 manual test cases classified according to their intended testing conditions.

| Test Case Classification | Count |
|---|---:|
| Happy Path | 37 |
| Negative | 13 |
| **Total** | **50** |

**Happy Path Testing:** Validates expected application behavior under normal conditions and with valid inputs.

**Negative Testing:** Validates application behavior when invalid inputs, missing information, or other unexpected conditions are encountered.

These classifications describe the intended test conditions. They do not indicate whether the corresponding test cases have passed or failed during execution.

---

## 📋 Test Case Design

The detailed test cases are documented in the Excel workbook.

The Master Test Cases sheet includes fields such as:

- Module ID
- Module Name
- Scenario ID
- Test Scenario
- Test Case ID
- Test Case Title
- Test Data
- Preconditions
- Step Number
- Test Step Description
- Expected Result
- Identification of Test Case
- Actual Result
- Execution Status
- Priority
- Defect ID
- Comments

The test cases are organized by module and scenario to improve readability and traceability.

The Master Test Cases sheet serves as the primary reference for the detailed test suite.

---

## 🔗 Test Traceability

The workbook includes a traceability sheet that maps test scenarios to their associated test cases.

The relationship can be represented as:

```text
Test Scenario
      |
      v
Test Case ID
      |
      v
Detailed Test Steps
      |
      v
Expected Result
```

This structure helps organize test coverage and makes it easier to identify the test cases associated with a particular scenario.

**Note:** The current traceability focuses on Scenario-to-Test Case mapping. A formal requirements-based Requirements Traceability Matrix (RTM) would require an appropriate set of business or functional requirements.

---

## ▶️ Test Execution

The workbook includes a Test Execution sheet to support execution tracking.

Relevant execution information includes:

- Test Case ID
- Module
- Test Scenario
- Test Case Title
- Priority
- Test Case Classification
- Actual Result
- Execution Status
- Defect ID
- Comments

Suggested execution statuses include:

- Not Executed
- Pass
- Fail
- Blocked

A test case should be marked as Pass or Fail only after it has been executed and its actual result has been compared with the expected result.

Execution results should reflect actual observations rather than assumptions.

---

## 📝 Test Plan

A separate test plan document describes the overall testing approach and provides a structured overview of the project.

The test plan covers:

- Introduction and objectives
- Testing scope
- Modules under test
- Testing approach and techniques
- Test environment
- Test data management
- Entry and exit criteria
- Test deliverables
- Defect management approach
- Risks and mitigation
- Assumptions and limitations
- Test execution strategy

The test plan is available in two formats:

- [OpenCart Test Plan — PDF](Test-Plan/OpenCart-Test-Plan.pdf)
- [OpenCart Test Plan — Word](Test-Plan/OpenCart-Test-Plan.docx)

The PDF is intended for convenient viewing and sharing, while the Word document can be used for future edits.

---

## 🔍 Testing Techniques

The project demonstrates or provides a foundation for applying the following manual testing techniques:

- Positive Testing
- Negative Testing
- Functional Testing
- Input Validation Testing
- UI Testing
- Navigation Testing
- Error Message Validation
- End-to-End Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Regression Testing

The applicability of each technique depends on the individual test scenario and its validation requirements.

---

## 🔄 Software Testing Life Cycle (STLC)

The project documentation is organized around the following Software Testing Life Cycle activities:

1. Requirement and application understanding
2. Test scenario identification
3. Test case design
4. Test data preparation
5. Test execution
6. Result recording
7. Defect reporting, where applicable
8. Retesting and regression testing, where applicable
9. Test closure and documentation review

These activities provide a structured approach to planning, documenting, and performing software testing.

The project documentation represents the testing artifacts developed for the application. Actual execution and defect findings should be documented separately when verified.

---

## 📁 Repository Structure

The repository is organized to make the primary QA documentation easy to locate and review.

```text
opencart-manual-testing/
│
├── README.md
│
├── Test-Plan/
│   ├── OpenCart-Test-Plan.pdf
│   └── OpenCart-Test-Plan.docx
│
└── Test-Documentation/
    └── OpenCart_QA_Test_Cases.xlsx
```

The README provides a quick overview of the project and selected test cases.

The test plan explains the testing strategy, while the Excel workbook contains the detailed test documentation.

Additional documentation and verified testing evidence may be added as the project evolves.

---

## 🛠️ Tools & Technologies

- **OpenCart:** Application under test
- **Microsoft Excel:** Test case design and QA documentation
- **Microsoft Word:** Test plan documentation
- **PDF:** Shareable test plan format
- **Git:** Version control
- **GitHub:** Repository hosting and portfolio presentation
- **Web Browser:** Application access and functional validation

---

## 💡 Key Learning Outcomes

This project provides practical experience in:

- Understanding e-commerce application workflows
- Identifying test scenarios from application functionality
- Designing structured manual test cases
- Writing clear test steps and expected results
- Creating positive and negative test conditions
- Organizing test cases using module and scenario identifiers
- Maintaining scenario-to-test-case traceability
- Structuring test execution documentation
- Applying fundamental software testing concepts
- Presenting QA documentation in a professional portfolio

---

## 🚀 Future Enhancements

Potential future enhancements include:

- Executing additional test cases and recording verified results
- Documenting reproducible defects with screenshots
- Adding API test cases using Postman
- Performing database validation using SQL
- Automating selected workflows using Selenium or Playwright
- Expanding cross-browser and responsive testing
- Adding execution metrics and a regression test suite
- Improving test coverage based on additional application workflows

These enhancements can be introduced incrementally as the project progresses.

---

## 👨‍💻 Author

**Prakirnakeshi Pragya**

Aspiring QA Engineer

This project is part of my QA portfolio and demonstrates my practical understanding of manual testing, test case design, test documentation, and software quality assurance.

---

## ⭐ Project Highlights

**50 Test Cases | 11 Modules | Happy Path & Negative Testing | Test Execution Tracking | Test Traceability**
