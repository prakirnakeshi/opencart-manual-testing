# OpenCart Manual Testing Project

A practical Manual QA Testing project focused on validating the functionality
of an e-commerce application using structured test scenarios and test cases.

This project demonstrates an understanding of manual testing fundamentals,
the Software Testing Life Cycle (STLC), positive and negative testing,
test execution tracking, and test traceability.

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
- Design clear and structured manual test cases.
- Cover positive and negative testing conditions.
- Validate expected application behavior.
- Organize test documentation professionally.
- Maintain traceability between test scenarios and test cases.
- Track test execution status and record actual results.
- Demonstrate practical knowledge of manual software testing.

---

## 🏗️ Application Under Test

The application under test is the OpenCart e-commerce application.

The project focuses on validating common e-commerce workflows, including
user registration, authentication, product browsing, searching, wishlist
management, shopping cart operations, checkout, and order placement.

The objective is to assess whether important application features behave
as expected under normal and invalid input conditions.

---

## 🧪 Testing Scope

The project covers the following 11 modules:

### 1. Homepage and Featured Products

- Homepage loading and display.
- Featured product visibility.
- Product navigation.
- Product link functionality.

### 2. Header and Navigation

- Navigation menu functionality.
- Header links.
- Navigation between application pages.
- Account and shopping cart navigation.

### 3. Currency

- Currency selection.
- Currency display.
- Product price updates after currency selection.
- Currency behavior during navigation.

### 4. User Registration

- Registration with valid information.
- Mandatory field validation.
- Invalid email format.
- Duplicate email registration.
- Password validation.
- Password confirmation.
- Terms and conditions validation.

### 5. Login and Authentication

- Login with valid credentials.
- Login with invalid credentials.
- Login with blank fields.
- Invalid email format.
- Password masking.
- Logout functionality.

### 6. Wishlist and Product Comparison

- Adding products to the wishlist.
- Removing products from the wishlist.
- Wishlist access for logged-out users.
- Adding products to comparison.
- Product comparison functionality.

### 7. Shopping Cart

- Adding products to the cart.
- Adding multiple products.
- Updating product quantities.
- Removing products.
- Cart subtotal and total validation.
- Invalid quantity handling.
- Empty cart behavior.

### 8. Checkout

- Proceeding to checkout with a valid cart.
- Entering billing and shipping information.
- Shipping method selection.
- Order review.
- Mandatory field validation.
- Invalid information handling.
- Attempting checkout with an empty cart.

### 9. Product Search

- Searching by exact product name.
- Searching by partial product name.
- Case variation in search terms.
- Empty search input.
- Search with no matching results.
- Special characters in search input.
- Leading and trailing spaces.

### 10. My Account

- Accessing the account dashboard.
- Viewing customer information.
- Address management.
- Password change functionality.
- Mandatory field validation.
- Invalid information handling.
- Incorrect current password.
- Password confirmation validation.

### 11. Payment and Order Placement

- Payment method selection.
- Order placement workflow.
- Order confirmation.
- Invalid payment information handling.
- Navigation during order placement.
- Duplicate order prevention.

The exact coverage of each module is documented in the Excel workbook.

---

## 📊 Test Coverage

The project contains 50 manual test cases classified according to their
testing intent.

| Test Case Classification | Count |
|---|---:|
| Happy Path | 37 |
| Negative | 13 |
| **Total** | **50** |

Happy path test cases validate expected behavior under valid conditions.

Negative test cases validate application behavior when invalid inputs,
missing information, or other unexpected conditions are encountered.

These classifications describe the intended test conditions and do not
indicate whether a test case has passed or failed during execution.

---

## 📋 Test Case Documentation

The detailed test cases are maintained in the Excel workbook:

`Test-Documentation/OpenCart_QA_Test_Cases.xlsx`

The Master Test Cases sheet contains the following information:

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
- Actual Result
- Execution Status
- Priority
- Identification of Test Case
- Defect ID and Comments

The workbook also contains supporting sheets for test scenarios,
test execution, traceability, and summary reporting.

The Master Test Cases sheet serves as the primary detailed test-case
repository.

---

## 🔗 Test Traceability

The workbook includes a traceability sheet that maps test scenarios
to their associated test cases.

The relationship can be represented as:

Test Scenario
      ↓
Test Case ID
      ↓
Detailed Test Steps
      ↓
Expected Result

This structure helps organize test coverage and makes it easier to
identify which test cases validate a particular scenario.

**Note:** The current traceability focuses on Scenario-to-Test Case
mapping. A formal requirements-based Requirements Traceability Matrix
(RTM) would require an appropriate set of business or functional
requirements.

---

## ▶️ Test Execution

The workbook includes a Test Execution sheet to support test execution
tracking.

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

Actual execution results should be recorded after performing the
corresponding test cases against the application.

---

## 📝 Test Plan

A separate test plan document describes the overall testing approach,
scope, objectives, test environment, entry and exit criteria, test
deliverables, risks, assumptions, and test execution strategy.

The test plan is available in the following formats:

- `Test-Plan/OpenCart-Test-Plan.pdf`

The PDF version is intended for convenient viewing, while the Word
version can be used for future edits.

---

## 🔍 Testing Techniques

The project demonstrates or provides a foundation for applying the
following manual testing techniques:

- Positive Testing
- Negative Testing
- Functional Testing
- Input Validation Testing
- Boundary Value Analysis
- Equivalence Partitioning
- UI Testing
- Navigation Testing
- Error Message Validation
- End-to-End Testing
- Regression Testing

The applicability of each technique depends on the particular test
scenario and its validation requirements.

---

## 🔄 Software Testing Life Cycle (STLC)

The project documentation is organized around the following STLC
activities:

1. Requirement and application understanding.
2. Test scenario identification.
3. Test case design.
4. Test data preparation.
5. Test execution.
6. Result recording.
7. Defect reporting, where applicable.
8. Retesting and regression testing, where applicable.
9. Test closure and documentation review.

These activities provide a structured approach to planning and
performing software testing.

---

## 📁 Repository Structure

The repository is organized to make the primary documentation easy
to locate and review.

```text
opencart-manual-testing/
│
├── README.md
│
├── Test-Plan/
│   ├── OpenCart-Test-Plan.pdf
│
└── Test-Documentation/
    └── OpenCart_QA_Test_Cases.xlsx
