# E-commerce Website Manual Testing — Test Scenarios

## 1. Objective

The objective of this document is to identify test scenarios for validating the main shopping workflows of the SauceDemo practice application.

**Application Under Test:** https://www.saucedemo.com/

## 2. Login Scenarios

**TS001:** Verify login with valid credentials.

**TS002:** Verify login with an invalid username.

**TS003:** Verify login with an incorrect password.

**TS004:** Verify login when both credentials are invalid.

**TS005:** Verify login with both username and password fields empty.

**TS006:** Verify login with the username field empty.

**TS007:** Verify login with the password field empty.

**TS008:** Verify appropriate error messages for failed login attempts.

## 3. Product Listing Scenarios

**TS009:** Verify that the products page displays available products after successful login.

**TS010:** Verify that each product displays its name and price.

**TS011:** Verify that product images are displayed correctly.

**TS012:** Verify product sorting by name in ascending order, if supported.

**TS013:** Verify product sorting by name in descending order, if supported.

**TS014:** Verify product sorting by price from low to high, if supported.

**TS015:** Verify product sorting by price from high to low, if supported.

**TS016:** Verify navigation to a product details page, if supported.

## 4. Shopping Cart Scenarios

**TS017:** Verify that a product can be added to the cart.

**TS018:** Verify that the cart item count updates after adding a product.

**TS019:** Verify that multiple products can be added to the cart.

**TS020:** Verify that the selected product details appear in the cart.

**TS021:** Verify that the displayed product price matches the listing price.

**TS022:** Verify that a product can be removed from the cart.

**TS023:** Verify that the cart count updates after removing a product, if displayed.

**TS024:** Verify the behavior when the cart contains no products.

**TS025:** Verify navigation between the products page and the cart.

## 5. Checkout Scenarios

**TS026:** Verify that checkout can be initiated from the cart.

**TS027:** Verify checkout with all required fields completed using fictional test data.

**TS028:** Verify checkout when the first name is empty.

**TS029:** Verify checkout when the last name is empty.

**TS030:** Verify checkout when the postal code is empty.

**TS031:** Verify that appropriate validation messages are displayed for missing required fields.

**TS032:** Verify that entering valid fictional details allows the workflow to continue.

## 6. Order Summary and Completion Scenarios

**TS033:** Verify that selected products appear in the order summary.

**TS034:** Verify that product prices in the order summary are correct.

**TS035:** Verify that the displayed subtotal matches the sum of item prices.

**TS036:** Verify that tax and final total are calculated as displayed by the application.

**TS037:** Verify that the order completion page appears after completing the supported checkout workflow.

**TS038:** Verify that the completion message is displayed correctly.

**TS039:** Verify the cart state after completing an order.

## 7. Navigation and Session Scenarios

**TS040:** Verify logout functionality.

**TS041:** Verify that logging out returns the user to the login page.

**TS042:** Verify that protected pages cannot be accessed without authentication, where applicable.

**TS043:** Verify browser Back behavior after logout.

**TS044:** Verify whether cart contents persist when navigating between supported pages.

## 8. UI and Usability Scenarios

**TS045:** Verify that buttons and links have clear labels.

**TS046:** Verify that product names and prices are readable.

**TS047:** Verify that validation and error messages are understandable.

**TS048:** Verify keyboard navigation across important controls.

**TS049:** Verify that the page layout remains usable at different browser window sizes.

## 9. Negative and Error-Handling Scenarios

**TS050:** Verify that repeated clicks on an Add to Cart button behave correctly.

**TS051:** Verify that invalid checkout inputs are handled appropriately.

**TS052:** Verify that navigating through the shopping workflow does not cause unexpected page errors.

**TS053:** Verify that unsupported or unavailable actions are handled gracefully.

## 10. Testing Notes

- Confirm that each scenario applies to the current version of the practice application.
- Features marked "if supported" should only be tested if they are available.
- Use only fictional test data and authorized demo accounts.
- Record the actual result after executing each scenario.
- Mark scenarios as Passed or Failed only after execution.
- Document reproducible defects with steps and supporting evidence.

## 11. Status Summary

**Total Scenarios Documented:** 53

**Execution Status:** Not Executed.

**Note:** These are planned test scenarios. Actual results will be recorded after manual execution.
