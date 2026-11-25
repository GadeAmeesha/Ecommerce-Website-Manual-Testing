
# E-commerce Website Manual Testing — Test Plan

## 1. Project Overview

This project focuses on manual testing of an e-commerce demo application to validate shopping functionality, input validation, navigation, user workflows, and overall application quality.

- **Application Under Test:** https://www.saucedemo.com/
- **Testing Type:** Manual Testing
- **Project Type:** QA Portfolio Project
- **Total Test Cases:** 60
- **Execution Status:** Completed (User Reported)
- **Result Verification:** Pending

---

## 2. Objectives

- Verify login functionality using valid and invalid credentials.
- Validate product listing, descriptions, images, and prices.
- Verify product sorting functionality.
- Test add-to-cart and remove-from-cart functionality.
- Verify cart contents and item count.
- Validate checkout form fields.
- Verify subtotal, tax, and final total calculations.
- Validate order completion and confirmation messages.
- Verify navigation, logout, and session behavior.
- Identify and document reproducible defects.
- Evaluate application usability and compatibility.
- Perform retesting and regression testing where applicable.

---

## 3. Scope of Testing

### In Scope

- Valid and invalid login credentials.
- Mandatory field validation.
- Password masking and error messages.
- Product listing and product details.
- Product sorting by name and price.
- Adding and removing products from the cart.
- Shopping cart item count.
- Empty cart functionality.
- Checkout form validation.
- Special-character and long-input scenarios.
- Order summary and total amount calculation.
- Order completion workflow.
- Logout and session management.
- Browser navigation.
- UI and usability checks.
- Responsive layout checks.
- Cross-browser compatibility.
- Positive and negative testing.
- Boundary scenarios.
- Regression testing where applicable.

### Out of Scope

- Real payment processing.
- Real customer information.
- Production database modifications.
- Unauthorized security testing.
- Load and stress testing.
- Third-party payment gateway integration.
- Features unavailable in the demo application.

---

## 4. Testing Approach

The project follows a structured manual testing approach based on the Software Testing Life Cycle (STLC).

### Phase 1: Requirement Analysis

- Identified available application functionality.
- Analyzed shopping-related user workflows.
- Identified positive and negative scenarios.

### Phase 2: Test Planning

- Defined testing objectives and scope.
- Identified testing types and techniques.
- Established entry and exit criteria.
- Identified risks and limitations.

### Phase 3: Test Case Development

- Prepared 60 manual test cases.
- Defined test scenarios and preconditions.
- Prepared suitable test data.
- Documented execution steps and expected results.

### Phase 4: Test Environment Setup

- Used the SauceDemo practice application.
- Prepared demo login credentials.
- Used fictional checkout information.

### Phase 5: Test Execution

- Manual execution was reported as completed.
- Original execution records were not retained.
- Results were reconstructed based on standard application behavior.
- Reconstructed results require verification before final approval.

### Phase 6: Defect Reporting

- Identified areas requiring additional verification.
- Prepared a structured defect reporting process.
- Confirmed defects will be documented after reproduction.

### Phase 7: Test Closure

- Prepared the reconstructed test execution summary.
- Documented remaining verification requirements.
- Final test closure remains pending result verification.

---

## 5. Testing Types and Techniques

| Testing Type / Technique | Application Area |
|---|---|
| Functional Testing | Login, products, cart, checkout and logout |
| Positive Testing | Valid credentials and successful workflows |
| Negative Testing | Invalid credentials and incomplete inputs |
| Input Validation Testing | Login and checkout fields |
| Equivalence Partitioning | Valid and invalid input categories |
| Boundary Value Analysis | Input length and boundary scenarios |
| Decision Table Testing | Login and checkout input combinations |
| State Transition Testing | Login, logout, cart and order states |
| UI Testing | Buttons, labels, images and page layout |
| Usability Testing | Navigation, readability and accessibility |
| Compatibility Testing | Different browsers and screen sizes |
| End-to-End Testing | Login to successful order completion |
| Retesting | Reverification of identified issues |
| Regression Testing | Related functionality after application changes |

Note: The table represents planned testing coverage. Individual technique execution and results require verification where original records are unavailable.

---

## 6. Test Environment

| Parameter | Details |
|---|---|
| Application | SauceDemo |
| Application URL | https://www.saucedemo.com/ |
| Application Type | Web-based e-commerce demo |
| Operating System | Original execution details not retained |
| Browser | Original execution details not retained |
| Browser Version | Not recorded |
| Testing Method | Manual Testing |
| Test Data | Demo credentials and fictional inputs |
| Test Management | Markdown documentation |
| Version Control | Git |
| Repository Management | GitHub |
| Test Evidence | Original execution evidence unavailable |

### Test Data

| Field | Test Data |
|---|---|
| Valid Username | standard_user |
| Valid Password | secret_sauce |
| Invalid Username | invalid_user_123 |
| Invalid Password | wrong_password |
| First Name | Test |
| Last Name | User |
| Postal Code | 500001 |
| Special Character Input | Test@User |
| Empty Input | Blank fields |
| Long Input | Extended fictional text |

---

## 7. Entry Criteria

Testing can begin when:

- The demo application is accessible.
- Application workflows are identified.
- Test scenarios are prepared.
- Test cases are documented.
- Suitable test data is available.
- The test environment is ready.

**Entry Criteria Status:** Satisfied based on reported manual execution.

---

## 8. Exit Criteria

Testing can be considered complete when:

- All planned test cases have been executed or their status documented.
- Actual results have been verified.
- Failed test cases have been investigated.
- Reproducible defects have been documented.
- Required retesting has been completed.
- Regression testing has been performed where applicable.
- The final execution report has been updated.
- Remaining risks and limitations have been documented.

**Exit Criteria Status:** Partially satisfied.

Final test closure is pending verification of reconstructed results and any applicable defect investigation.

---

## 9. Defect Reporting Process

Each confirmed defect should include:

- Defect ID
- Related Test Case ID
- Defect Title
- Module Name
- Test Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Screenshot or Evidence
- Defect Status

### Defect Severity Classification

| Severity | Description |
|---|---|
| Critical | Application or major workflow becomes unusable |
| High | Important functionality does not work correctly |
| Medium | Partial functionality is affected |
| Low | Minor UI, alignment or cosmetic issue |

### Defect Priority Classification

| Priority | Description |
|---|---|
| P1 - High | Requires immediate attention |
| P2 - Medium | Requires resolution within a planned cycle |
| P3 - Low | Can be resolved in a future update |

### Defect Life Cycle

New → Assigned → Open → Fixed → Retest → Verified → Closed

If the issue persists during retesting, the defect can be reopened.

**Current Defect Status:** No confirmed defect count has been established because the original execution records are unavailable.

---

## 10. Test Execution Summary

| Module | Total Test Cases | Provisional Pass | Needs Verification |
|---|---:|---:|---:|
| Login | 10 | 10 | 0 |
| Products and Sorting | 10 | 9 | 1 |
| Shopping Cart | 10 | 10 | 0 |
| Checkout | 10 | 7 | 3 |
| Order Summary | 8 | 7 | 1 |
| Navigation and Session | 4 | 2 | 2 |
| UI and Compatibility | 5 | 1 | 4 |
| Negative and Regression | 3 | 1 | 2 |
| **Total** | **60** | **47** | **13** |

### Execution Metrics

| Metric | Result |
|---|---:|
| Total Test Cases | 60 |
| Provisional Passed | 47 |
| Needs Verification | 13 |
| Confirmed Passed | Not Established |
| Confirmed Failed | Not Established |
| Confirmed Defects | Not Established |
| Provisional Pass Percentage | 78.33% |
| Additional Verification Percentage | 21.67% |

These metrics represent reconstructed results rather than verified execution evidence.

---

## 11. Risks and Limitations

| Risk | Impact | Mitigation |
|---|---|---|
| Application changes | Existing test cases may become outdated | Review and update test cases |
| Website unavailability | Test execution may be interrupted | Retry when the application is available |
| Missing original execution records | Actual results cannot be independently confirmed | Re-execute test cases and capture evidence |
| Browser-specific behavior | Results may vary across environments | Perform cross-browser testing |
| Limited application requirements | Some expected behaviors may be unclear | Document assumptions and validation rules |
| Demo application limitations | Real payment and production workflows cannot be tested | Restrict testing to available functionality |
| Missing regression baseline | Regression results cannot be established | Document application changes and execute related tests |

---

## 12. Project Deliverables

| Deliverable | Status |
|---|---|
| Test Plan | Completed |
| Test Scenarios | Documented within test cases |
| Test Cases | Completed - 60 Test Cases |
| Test Data | Documented |
| Manual Test Execution | Completed - User Reported |
| Actual Results Documentation | Reconstructed |
| Test Execution Report | Prepared - Provisional |
| Defect Reporting Documentation | Pending confirmed defects |
| Screenshots and Test Evidence | Original evidence unavailable |
| Retesting | Pending verification |
| Regression Testing | Pending applicable changes |
| Final Test Closure | Pending |

---

## 13. Tools and Technologies

- SauceDemo
- Web Browser
- Manual Testing
- Markdown
- Git
- GitHub

---

## 14. Skills Demonstrated

- Software Testing Life Cycle (STLC)
- Requirement Analysis
- Test Planning
- Test Scenario Preparation
- Test Case Design
- Test Data Preparation
- Manual Test Execution
- Functional Testing
- Positive and Negative Testing
- Test Result Documentation
- Defect Reporting
- Test Execution Metrics
- Git and GitHub Documentation

---

## 15. Project Status

- **Planning Status:** Completed
- **Test Design Status:** Completed
- **Total Test Cases:** 60
- **Manual Execution Status:** Completed (User Reported)
- **Result Documentation:** Reconstructed
- **Provisional Passed:** 47
- **Needs Additional Verification:** 13
- **Defect Confirmation:** Pending
- **Final Test Closure:** Pending

---

## 16. Conclusion

The SauceDemo E-commerce Website Manual Testing project
was designed to evaluate core shopping functionality,
input validation, navigation, session management, and
overall application usability.

A total of 60 manual test cases were prepared across
eight testing areas.

Manual testing was reported as completed. However, the
original execution records were not retained.

Based on reconstructed results, 47 test cases are
provisionally classified as passed, while 13 require
additional verification.

The reconstructed results must be verified before
establishing a confirmed pass rate or defect count.

This project demonstrates practical knowledge of manual
software testing, structured test documentation, test
case design, execution reporting, and QA processes.

---

## Author

**Gade Ameesha**

Software Developer | QA Engineer

GitHub: https://github.com/GadeAmeesha

LinkedIn: https://www.linkedin.com/in/gade-ameesha/
