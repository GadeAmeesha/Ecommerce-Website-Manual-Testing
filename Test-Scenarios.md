
# E-commerce Website Manual Testing — Test Scenarios

## 1. Project Overview

- **Project Name:** E-commerce Website Manual Testing
- **Application Under Test:** https://www.saucedemo.com/
- **Testing Type:** Manual Testing
- **Project Type:** QA Portfolio Project
- **Total Test Scenarios:** 53
- **Total Test Cases:** 60
- **Execution Status:** Completed (User Reported)
- **Result Status:** Reconstructed — Pending Verification

---

## 2. Objective

The objective of this document is to identify and validate
the main shopping workflows of the SauceDemo application.

The testing scope includes:

- Authentication and authorization
- Product listing and sorting
- Shopping cart functionality
- Checkout form validation
- Order summary and completion
- Navigation and session management
- UI and usability
- Negative testing and error handling

---

## 3. Login Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS001 | Verify login with valid credentials | TC001 | User navigated to the products page successfully. | Provisional Pass |
| TS002 | Verify login with an invalid username | TC002 | Invalid username was rejected. | Provisional Pass |
| TS003 | Verify login with an incorrect password | TC003 | Incorrect password was rejected. | Provisional Pass |
| TS004 | Verify login with both credentials invalid | TC004 | Access was denied with an error message. | Provisional Pass |
| TS005 | Verify login with both fields empty | TC005 | Required field validation was displayed. | Provisional Pass |
| TS006 | Verify login with username empty | TC006 | Username required validation was displayed. | Provisional Pass |
| TS007 | Verify login with password empty | TC007 | Password required validation was displayed. | Provisional Pass |
| TS008 | Verify appropriate login error messages | TC008, TC010 | Understandable error messages were displayed for invalid login attempts. | Provisional Pass |

---

## 4. Product Listing and Sorting Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS009 | Verify available products after login | TC011 | Available products were displayed successfully. | Provisional Pass |
| TS010 | Verify product names and prices | TC012, TC013 | Product names and prices were displayed consistently. | Provisional Pass |
| TS011 | Verify product images | TC014 | Image loading and product-image mapping require confirmation. | Needs Verification |
| TS012 | Verify name sorting in ascending order | TC016 | Products were sorted from A to Z. | Provisional Pass |
| TS013 | Verify name sorting in descending order | TC017 | Products were sorted from Z to A. | Provisional Pass |
| TS014 | Verify price sorting from low to high | TC018 | Products were arranged in ascending price order. | Provisional Pass |
| TS015 | Verify price sorting from high to low | TC019 | Products were arranged in descending price order. | Provisional Pass |
| TS016 | Verify navigation to product details | TC012, TC015 | Product details and descriptions were displayed. | Provisional Pass |

---

## 5. Shopping Cart Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS017 | Verify adding a product to the cart | TC021 | Selected product was added successfully. | Provisional Pass |
| TS018 | Verify cart count after adding a product | TC023 | Cart count increased according to selected items. | Provisional Pass |
| TS019 | Verify adding multiple products | TC022 | Multiple selected products appeared in the cart. | Provisional Pass |
| TS020 | Verify selected product details in the cart | TC024 | Correct product details were displayed. | Provisional Pass |
| TS021 | Verify cart price against listing price | TC024 | Cart price matched the product listing price. | Provisional Pass |
| TS022 | Verify removing a product from the cart | TC025 | Selected product was removed successfully. | Provisional Pass |
| TS023 | Verify cart count after removing a product | TC025, TC026 | Cart count after removal requires explicit confirmation. | Needs Verification |
| TS024 | Verify empty cart behavior | TC026, TC027 | Empty cart was displayed without unexpected errors. | Provisional Pass |
| TS025 | Verify navigation between products and cart | TC028, TC029 | Navigation between products and cart worked successfully. | Provisional Pass |

---

## 6. Checkout Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS026 | Verify checkout initiation | TC031 | Checkout information page opened successfully. | Provisional Pass |
| TS027 | Verify checkout with valid fictional details | TC032 | Valid information was accepted. | Provisional Pass |
| TS028 | Verify checkout with first name empty | TC033 | First Name is required validation was displayed. | Provisional Pass |
| TS029 | Verify checkout with last name empty | TC034 | Last Name is required validation was displayed. | Provisional Pass |
| TS030 | Verify checkout with postal code empty | TC035 | Postal Code is required validation was displayed. | Provisional Pass |
| TS031 | Verify missing required field validation | TC033, TC034, TC035, TC036 | Checkout was prevented when mandatory fields were empty. | Provisional Pass |
| TS032 | Verify continuation with valid details | TC032 | User navigated to the checkout overview page. | Provisional Pass |

---

## 7. Order Summary and Completion Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS033 | Verify selected products in order summary | TC041 | Selected products appeared in the order summary. | Provisional Pass |
| TS034 | Verify order summary product prices | TC042 | Product prices matched the cart prices. | Provisional Pass |
| TS035 | Verify subtotal calculation | TC043 | Subtotal matched the sum of selected product prices. | Provisional Pass |
| TS036 | Verify tax and final total calculation | TC044, TC045 | Final total matched subtotal plus displayed tax; the tax rule requires confirmation. | Needs Verification |
| TS037 | Verify order completion page | TC046 | Order completion page was displayed successfully. | Provisional Pass |
| TS038 | Verify order confirmation message | TC047 | Thank you for your order message was displayed. | Provisional Pass |
| TS039 | Verify cart state after order completion | TC048 | Cart was cleared after order completion. | Provisional Pass |

---

## 8. Navigation and Session Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS040 | Verify logout functionality | TC049 | User was logged out successfully. | Provisional Pass |
| TS041 | Verify redirection after logout | TC049 | User was redirected to the login page. | Provisional Pass |
| TS042 | Verify protected page access without authentication | TC050 | Protected page access requires additional verification. | Needs Verification |
| TS043 | Verify browser Back behavior after logout | TC050 | Browser history behavior after logout requires confirmation. | Needs Verification |
| TS044 | Verify cart persistence during navigation | TC030 | Selected products remained in the cart during navigation. | Provisional Pass |

---

## 9. UI and Usability Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS045 | Verify clear button and link labels | TC053 | Button labels were understandable; link labels require confirmation. | Needs Verification |
| TS046 | Verify product name and price readability | TC055 | Readability and alignment require additional verification. | Needs Verification |
| TS047 | Verify understandable validation messages | TC008, TC033, TC034, TC035 | Relevant validation messages were displayed. | Provisional Pass |
| TS048 | Verify keyboard navigation | TC054 | Keyboard accessibility and focus order require verification. | Needs Verification |
| TS049 | Verify layout at different window sizes | TC056 | Responsive layout requires verification at multiple resolutions. | Needs Verification |

---

## 10. Negative and Error-Handling Scenarios

| Scenario ID | Test Scenario | Test Case ID | Reconstructed Result | Status |
|---|---|---|---|---|
| TS050 | Verify repeated Add to Cart clicks | TC058 | Add to Cart changed to Remove after selection, preventing unintended duplicate additions through the same button. | Provisional Pass |
| TS051 | Verify invalid checkout input handling | TC037, TC038, TC039, TC059 | Whitespace, special characters and long-input validation require confirmation. | Needs Verification |
| TS052 | Verify unexpected errors during shopping workflow | TC031, TC032, TC046, TC052 | Core checkout flow is provisionally successful, but complete navigation error coverage requires verification. | Needs Verification |
| TS053 | Verify unsupported or unavailable actions | No dedicated test case | Unsupported-action handling requires a dedicated test case and execution. | Needs Verification |

---

## 11. Testing Techniques

| Testing Technique | Scenario Coverage |
|---|---|
| Equivalence Partitioning | TS001–TS007, TS027–TS030, TS051 |
| Boundary Value Analysis | TS051 — requires defined input limits and boundary test data |
| Decision Table Testing | TS001–TS007, TS027–TS031 |
| State Transition Testing | TS017–TS024, TS037–TS044 |
| Error Guessing | TS043, TS050–TS053 |
| Use Case Testing | TS001, TS017, TS026, TS027, TS037 |
| Exploratory Testing | TS011, TS045–TS049, TS052, TS053 |

The above table identifies applicable testing techniques.
It does not establish that every technique was fully executed.

---

## 12. Testing Coverage

| Testing Type | Coverage |
|---|---|
| Functional Testing | Login, products, cart and checkout |
| Positive Testing | Valid credentials and successful shopping workflows |
| Negative Testing | Invalid credentials and invalid checkout inputs |
| Input Validation Testing | Login and checkout mandatory fields |
| UI Testing | Product images, buttons, labels and layout |
| Usability Testing | Navigation, readability and accessibility |
| Session Testing | Logout and protected page access |
| Compatibility Testing | Different window sizes and browsers |
| End-to-End Testing | Login to order completion |
| Retesting | Pending verification of reconstructed results |
| Regression Testing | Pending applicable application changes |

---

## 13. Scenario Execution Summary

| Module | Total Scenarios | Provisional Pass | Needs Verification |
|---|---:|---:|---:|
| Login | 8 | 8 | 0 |
| Product Listing and Sorting | 8 | 7 | 1 |
| Shopping Cart | 9 | 8 | 1 |
| Checkout | 7 | 7 | 0 |
| Order Summary and Completion | 7 | 6 | 1 |
| Navigation and Session | 5 | 3 | 2 |
| UI and Usability | 5 | 1 | 4 |
| Negative and Error Handling | 4 | 1 | 3 |
| **Total** | **53** | **41** | **12** |

---

## 14. Scenario Execution Metrics

| Metric | Result |
|---|---:|
| Total Test Scenarios | 53 |
| Provisional Passed Scenarios | 41 |
| Scenarios Requiring Verification | 12 |
| Provisional Pass Percentage | 77.36% |
| Verification Pending Percentage | 22.64% |
| Confirmed Passed Scenarios | Not Established |
| Confirmed Failed Scenarios | Not Established |
| Confirmed Defects | Not Established |

### Provisional Scenario Pass Percentage

Provisional Pass Percentage = (41 / 53) × 100

Provisional Pass Percentage = 77.36%

These percentages represent reconstructed classifications,
not a verified execution pass rate.

---

## 15. Related Test Case Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 60 |
| Provisional Passed Test Cases | 47 |
| Test Cases Requiring Additional Verification | 13 |
| Provisional Test Case Pass Percentage | 78.33% |
| Confirmed Defects | Not Established |

Note: Scenario-level and test-case-level metrics are different.
A single scenario can map to multiple test cases, and a test
case can support multiple scenarios.

---

## 16. Scenarios Requiring Additional Verification

| Scenario ID | Verification Required |
|---|---|
| TS011 | Product image loading and mapping |
| TS023 | Cart count after product removal |
| TS036 | Tax calculation rules |
| TS042 | Protected page access without authentication |
| TS043 | Browser Back behavior after logout |
| TS045 | Button and link label coverage |
| TS046 | Product readability and alignment |
| TS048 | Keyboard navigation and focus order |
| TS049 | Responsive layout at different resolutions |
| TS051 | Invalid checkout input validation |
| TS052 | Unexpected errors throughout the shopping workflow |
| TS053 | Unsupported-action handling |

---

## 17. Additional Test Case Coverage

The following test cases provide supplementary coverage
beyond the original scenario descriptions.

| Test Case ID | Additional Coverage |
|---|---|
| TC009 | Password masking |
| TC020 | Changing product sorting options |
| TC040 | Cancelling checkout |
| TC051 | Session behavior after browser refresh |
| TC052 | Browser Back navigation |
| TC057 | Cross-browser compatibility |
| TC060 | Regression testing after an application change |

TC052 also provides partial coverage for TS052.

TS053 requires a dedicated test case because the existing
test case document does not explicitly cover unsupported
or unavailable actions.

---

## 18. Testing Notes

- Use only authorized demo accounts and fictional test data.
- Verify that scenarios apply to the current application version.
- Record actual results immediately after test execution.
- Capture screenshots for important results and reproducible defects.
- Mark scenarios as confirmed Passed or Failed only after verification.
- Reproduce potential defects before reporting them.
- Document browser and operating system details.
- Maintain traceability between test scenarios and test cases.
- Update scenario status after retesting.
- Perform regression testing when applicable.
- Do not treat reconstructed results as verified execution evidence.

---

## 19. Project Deliverables

| Deliverable | Status |
|---|---|
| Test Plan | Completed |
| Test Scenarios | Completed - 53 Scenarios |
| Test Cases | Completed - 60 Test Cases |
| Test Data | Documented |
| Manual Execution | Completed - User Reported |
| Scenario and Test Case Mapping | Documented |
| Result Documentation | Reconstructed |
| Execution Summary | Prepared - Provisional |
| Bug Report | Pending Confirmed Defects |
| Test Evidence | Original Evidence Unavailable |
| Retesting | Pending Verification |
| Final Test Closure | Pending |

---

## 20. Final Project Status

- **Total Test Scenarios:** 53
- **Total Test Cases:** 60
- **Scenario Documentation:** Completed
- **Test Case Documentation:** Completed
- **Manual Execution:** Completed (User Reported)
- **Provisional Passed Scenarios:** 41
- **Scenarios Requiring Verification:** 12
- **Provisional Passed Test Cases:** 47
- **Test Cases Requiring Verification:** 13
- **Confirmed Defects:** Not Established
- **Final Result Verification:** Pending
- **Test Closure:** Pending

---

## 21. Conclusion

The SauceDemo E-commerce Website Manual Testing project
covers the major shopping workflows, including authentication,
product listing, sorting, shopping cart management, checkout,
order completion, navigation, and usability.

A total of 53 test scenarios and 60 test cases were documented.

Manual execution was reported as completed, but the original
execution records were not retained.

Based on reconstructed results, 41 scenarios are provisionally
classified as passed, while 12 require additional verification.

The project demonstrates practical knowledge of manual testing,
test scenario preparation, test case design, requirement
traceability, execution reporting, and software quality
assurance processes.

Final test closure remains pending verification of the
reconstructed results.

---

## Author

**Gade Ameesha**

Software Developer | QA Engineer

- GitHub: https://github.com/GadeAmeesha
- LinkedIn: https://www.linkedin.com/in/gade-ameesha/
