# E-commerce Website Manual Testing — Test Plan

## 1. Project Overview

This project focuses on manually testing an e-commerce demo application to verify shopping-related functionality, input validation, and user workflows.

**Application Under Test:** https://www.saucedemo.com/

**Testing Type:** Manual Testing

**Project Type:** QA Portfolio Project

## 2. Objectives

- Verify login functionality.
- Validate product listing and sorting.
- Test add-to-cart and remove-from-cart functionality.
- Verify cart contents and item quantities where supported.
- Validate checkout form fields.
- Verify order summary and order completion.
- Identify and document reproducible defects.
- Practice retesting and regression testing.

## 3. Scope of Testing

### In Scope

- Login with valid and invalid credentials.
- Empty-field validation.
- Product listing and product sorting.
- Adding products to the cart.
- Removing products from the cart.
- Cart item count and product details.
- Checkout form validation.
- Order summary and total amount display.
- Order completion workflow.
- UI and usability checks.
- Negative testing and boundary scenarios.

### Out of Scope

- Real payment processing.
- Testing real customer information.
- Production database modifications.
- Unauthorized security testing.
- Load and stress testing without suitable tools and authorization.
- Features that are not available in the demo application.

## 4. Testing Approach

The following approach will be used:

1. Explore the demo application.
2. Identify test scenarios based on available functionality.
3. Prepare suitable test data.
4. Write detailed test cases with steps and expected results.
5. Execute each test case manually.
6. Compare actual results with expected results.
7. Record Pass, Fail, Blocked, or Not Executed status.
8. Document confirmed defects with reproducible steps.
9. Retest fixes and perform regression testing where applicable.
10. Prepare the final test execution summary.

## 5. Testing Types

- Functional Testing
- Positive Testing
- Negative Testing
- Input Validation Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Decision Table Testing, where applicable
- State Transition Testing, where applicable
- UI and Usability Testing
- Compatibility Testing, where feasible
- Retesting
- Regression Testing

## 6. Test Environment

- **Application:** SauceDemo practice website
- **Operating System:** To be recorded during execution
- **Browser:** To be recorded during execution
- **Browser Version:** To be recorded during execution
- **Test Data:** Demo account and fictional sample inputs
- **Test Management:** Markdown files in GitHub
- **Evidence:** Screenshots, where appropriate

## 7. Entry Criteria

Testing can begin when:

- The demo application is accessible.
- The main application workflows are identified.
- Suitable test data is available.
- Test scenarios and test cases are prepared.
- The browser and test environment are ready.

## 8. Exit Criteria

Testing can be considered complete when:

- Planned test cases have been executed or their status has been documented.
- Failed test cases have been investigated.
- Reproducible defects have been documented.
- Required retesting and regression testing have been completed, where applicable.
- The execution report has been updated.
- Remaining limitations and risks have been recorded.

## 9. Defect Reporting Process

For each confirmed defect, record:

- Defect ID
- Defect title
- Environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Evidence
- Current status

A potential issue must be reproduced before it is reported as a confirmed defect.

## 10. Risks and Limitations

- The demo application may change or become temporarily unavailable.
- Some scenarios may depend on features supported by the application.
- Results may vary by browser or environment.
- The demo application may intentionally simulate certain behaviors.
- Security and performance coverage will be limited to appropriate, authorized checks.

## 11. Deliverables

The project will include:

- Test Plan
- Test Scenarios
- Test Cases
- Test Data
- Test Execution Report
- Bug Report documentation
- Screenshots or other relevant evidence

## 12. Project Status

**Planning Status:** Document prepared.

**Execution Status:** Pending actual manual execution.

**Defects:** No defects claimed as confirmed at the planning stage.

**Note:** Test results will be updated only after the relevant scenarios have been executed on the practice application.
