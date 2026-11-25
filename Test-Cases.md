
# E-commerce Website Manual Testing — Test Execution Results

## Project Information

- Project: E-commerce Website Manual Testing
- Application: https://www.saucedemo.com/
- Testing Type: Manual Testing
- Total Test Cases: 60
- Execution Status: Completed (User Reported)
- Results: Reconstructed, Pending Verification

## 1. Login Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC001 | Login with valid credentials | User navigated to the products page successfully. | Provisional Pass |
| TC002 | Login with invalid username | Login was rejected with an error message. | Provisional Pass |
| TC003 | Login with incorrect password | Application rejected the incorrect password. | Provisional Pass |
| TC004 | Login with invalid credentials | Login failed and access was denied. | Provisional Pass |
| TC005 | Both fields empty | Username required validation was displayed. | Provisional Pass |
| TC006 | Username empty | Username required error was displayed. | Provisional Pass |
| TC007 | Password empty | Password required error was displayed. | Provisional Pass |
| TC008 | Verify login error message | Appropriate error message was displayed without exposing credentials. | Provisional Pass |
| TC009 | Verify password masking | Password characters were masked. | Provisional Pass |
| TC010 | Repeated invalid login attempts | Invalid login attempts were consistently rejected. | Provisional Pass |

## 2. Product Listing and Sorting Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC011 | Verify product listing | Available products were displayed on the inventory page. | Provisional Pass |
| TC012 | Verify product names | Product names were consistent across listing and details pages. | Provisional Pass |
| TC013 | Verify product prices | Product prices matched across relevant pages. | Provisional Pass |
| TC014 | Verify product images | Image loading and product-image mapping require confirmation. | Needs Verification |
| TC015 | Verify product descriptions | Product descriptions were displayed correctly. | Provisional Pass |
| TC016 | Sort products A to Z | Products were sorted in ascending alphabetical order. | Provisional Pass |
| TC017 | Sort products Z to A | Products were sorted in descending alphabetical order. | Provisional Pass |
| TC018 | Sort prices low to high | Products were arranged from lowest to highest price. | Provisional Pass |
| TC019 | Sort prices high to low | Products were arranged from highest to lowest price. | Provisional Pass |
| TC020 | Change sorting option | Product order updated according to the selected sorting option. | Provisional Pass |

## 3. Shopping Cart Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC021 | Add one product to cart | Selected product was added and cart count increased. | Provisional Pass |
| TC022 | Add multiple products | Both selected products appeared in the cart. | Provisional Pass |
| TC023 | Verify cart item count | Cart count updated according to the selected items. | Provisional Pass |
| TC024 | Verify product details in cart | Product name, description and price matched the inventory details. | Provisional Pass |
| TC025 | Remove a product | Selected product was removed successfully. | Provisional Pass |
| TC026 | Remove all products | All selected products were removed from the cart. | Provisional Pass |
| TC027 | Verify empty cart | No products were displayed and the cart page remained accessible. | Provisional Pass |
| TC028 | Navigate to cart | Cart page opened successfully. | Provisional Pass |
| TC029 | Continue shopping | User returned to the products page. | Provisional Pass |
| TC030 | Cart state after navigation | Selected products remained in the cart after navigation. | Provisional Pass |

## 4. Checkout Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC031 | Start checkout | Checkout information page opened successfully. | Provisional Pass |
| TC032 | Checkout with valid information | User navigated to the checkout overview page. | Provisional Pass |
| TC033 | First name empty | First Name is required validation was displayed. | Provisional Pass |
| TC034 | Last name empty | Last Name is required validation was displayed. | Provisional Pass |
| TC035 | Postal code empty | Postal Code is required validation was displayed. | Provisional Pass |
| TC036 | All checkout fields empty | Checkout was prevented and required field validation was displayed. | Provisional Pass |
| TC037 | Leading and trailing spaces | Whitespace handling requires additional verification. | Needs Verification |
| TC038 | Special characters in name | Special-character acceptance and validation require confirmation. | Needs Verification |
| TC039 | Long input values | Maximum input length and layout behavior require confirmation. | Needs Verification |
| TC040 | Cancel checkout | User returned to the shopping cart page. | Provisional Pass |

## 5. Order Summary and Completion Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC041 | Verify order summary products | Selected products appeared in the order summary. | Provisional Pass |
| TC042 | Verify order summary prices | Product prices matched the shopping cart prices. | Provisional Pass |
| TC043 | Verify subtotal calculation | Subtotal matched the sum of selected product prices. | Provisional Pass |
| TC044 | Verify tax calculation | Tax was displayed, but the applicable calculation rule requires confirmation. | Needs Verification |
| TC045 | Verify final total | Final total matched the subtotal plus displayed tax. | Provisional Pass |
| TC046 | Complete the order | Order completion page was displayed successfully. | Provisional Pass |
| TC047 | Verify confirmation message | Thank you for your order message was displayed. | Provisional Pass |
| TC048 | Cart after order completion | Cart was cleared after successful order completion. | Provisional Pass |

## 6. Navigation and Session Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC049 | Verify logout | User was logged out and redirected to the login page. | Provisional Pass |
| TC050 | Protected page access after logout | Protected page access using browser Back requires confirmation. | Needs Verification |
| TC051 | Session after browser refresh | Login session and page state were retained after refresh. | Provisional Pass |
| TC052 | Browser Back navigation | Browser history and cart state require additional verification. | Needs Verification |

## 7. UI, Usability and Compatibility Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC053 | Verify button labels | Buttons displayed appropriate and understandable labels. | Provisional Pass |
| TC054 | Keyboard navigation | Keyboard accessibility and focus order require verification. | Needs Verification |
| TC055 | Page readability | Readability and alignment across all pages require confirmation. | Needs Verification |
| TC056 | Different window sizes | Responsive layout requires verification at multiple resolutions. | Needs Verification |
| TC057 | Cross-browser testing | Browser-specific execution results are unavailable. | Needs Verification |

## 8. Negative and Regression Testing

| Test Case ID | Test Scenario | Reconstructed Actual Result | Status |
|---|---|---|---|
| TC058 | Repeated Add to Cart clicks | Add to Cart changed to Remove after selection, preventing duplicate additions through the same button. | Provisional Pass |
| TC059 | Invalid workflow input | Complete invalid-input coverage requires additional verification. | Needs Verification |
| TC060 | Regression testing after a change | Regression results cannot be confirmed without a documented application change and retest. | Needs Verification |

---

## 9. Module-wise Execution Summary

| Module | Total | Provisional Pass | Needs Verification |
|---|---:|---:|---:|
| Login | 10 | 10 | 0 |
| Products and Sorting | 10 | 9 | 1 |
| Shopping Cart | 10 | 10 | 0 |
| Checkout | 10 | 7 | 3 |
| Order Summary | 8 | 7 | 1 |
| Navigation and Session | 4 | 2 | 2 |
| UI and Compatibility | 5 | 1 | 4 |
| Negative and Regression | 3 | 1 | 2 |
| Total | 60 | 47 | 13 |

## 10. Test Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 60 |
| Provisional Passed | 47 |
| Confirmed Failed | Not Established |
| Needs Verification | 13 |
| Provisional Pass Percentage | 78.33% |
| Verification Pending Percentage | 21.67% |
| Confirmed Defects | Not Established |

## 11. Areas Requiring Additional Verification

- Product image loading and mapping
- Checkout whitespace validation
- Special-character input validation
- Maximum input length validation
- Tax calculation rules
- Protected page access after logout
- Browser Back navigation
- Keyboard accessibility
- UI readability and alignment
- Responsive design
- Cross-browser compatibility
- Invalid workflow input handling
- Regression testing

## 12. Testing Coverage

- Functional Testing
- Positive Testing
- Negative Testing
- Input Validation Testing
- UI Testing
- Usability Testing
- Session Testing
- Navigation Testing
- Compatibility Testing
- End-to-End Testing
- Regression Testing

## 13. Final Conclusion

Manual testing was performed on the SauceDemo e-commerce
application covering login, product listing, sorting, shopping
cart, checkout, order completion and logout functionality.

A total of 60 test cases were documented. Based on reconstructed
results, 47 test cases are provisionally classified as passed,
while 13 require additional verification.

The original execution records were not retained. Therefore,
these reconstructed results must be verified before being
considered confirmed test execution evidence.

No confirmed defect count or final verified pass rate is
claimed without supporting execution records.

## 14. Tools Used

- SauceDemo
- Web Browser
- Manual Test Case Documentation
- Git
- GitHub

## 15. Project Status

- Test Case Documentation: Completed
- Manual Execution: Completed (User Reported)
- Result Documentation: Reconstructed
- Result Verification: Pending
- Defect Confirmation: Pending
