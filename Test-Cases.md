# E-commerce Website Manual Testing — Test Cases

## 1. Project Information

- **Project:** E-commerce Website Manual Testing
- **Application Under Test:** https://www.saucedemo.com/
- **Testing Type:** Manual Testing
- **Modules:** Login, Products, Sorting, Cart, Checkout, Order Summary, Logout
- **Total Test Cases:** 60
- **Execution Status:** Not Executed
- **Test Environment:** To be recorded during execution

## 2. Test Case Format

Each test case includes:
- Test Case ID
- Test Scenario
- Preconditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status

**Status definitions:** Pass, Fail, Blocked, Not Executed.

---

# 3. Login Testing

### TC001 — Login with valid credentials
**Precondition:** Login page is accessible.  
**Test Data:** Username: `standard_user`; Password: `secret_sauce`  
**Steps:**
1. Open the application.
2. Enter the username and password.
3. Click Login.  
**Expected Result:** User should navigate to the products page.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC002 — Login with an invalid username
**Precondition:** Login page is accessible.  
**Test Data:** Username: `invalid_user_123`; Password: `secret_sauce`  
**Steps:**
1. Enter the invalid username.
2. Enter the password.
3. Click Login.  
**Expected Result:** Login should be rejected with an appropriate error message.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC003 — Login with an incorrect password
**Test Data:** Username: `standard_user`; Password: `wrong_password`  
**Steps:**
1. Enter the valid username.
2. Enter the incorrect password.
3. Click Login.  
**Expected Result:** Login should be rejected.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC004 — Login with both credentials invalid
**Test Data:** Username: `unknown_user`; Password: `wrong_password`  
**Steps:**
1. Enter both invalid values.
2. Click Login.  
**Expected Result:** Login should fail without granting access.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC005 — Submit with both fields empty
**Steps:**
1. Leave username and password empty.
2. Click Login.  
**Expected Result:** Login should not proceed; appropriate validation should appear.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC006 — Submit with username empty
**Steps:**
1. Leave username empty.
2. Enter a password.
3. Click Login.  
**Expected Result:** Login should be rejected with suitable validation.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC007 — Submit with password empty
**Steps:**
1. Enter a username.
2. Leave password empty.
3. Click Login.  
**Expected Result:** Login should be rejected with suitable validation.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC008 — Verify login error message
**Steps:**
1. Enter invalid credentials.
2. Click Login.
3. Observe the error message.  
**Expected Result:** An understandable error message should be displayed without exposing sensitive information.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC009 — Verify password masking
**Steps:**
1. Enter a password in the password field.
2. Observe how the characters are displayed.  
**Expected Result:** Password characters should be masked by default.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC010 — Verify repeated invalid login attempts
**Steps:**
1. Submit invalid credentials several times in the demo environment.
2. Observe the response after each attempt.  
**Expected Result:** The application should handle repeated failures consistently according to its supported behavior.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 4. Product Listing Testing

### TC011 — Verify product listing
**Precondition:** User is logged in.  
**Steps:**
1. Open the products page.
2. Observe the product list.  
**Expected Result:** Available products should be displayed.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC012 — Verify product names
**Steps:**
1. Observe the product names.
2. Open individual product details where supported.
3. Compare the names.  
**Expected Result:** Product names should be displayed consistently.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC013 — Verify product prices
**Steps:**
1. Observe the displayed prices.
2. Compare a product's price on the listing and details page, if available.  
**Expected Result:** Product prices should be consistent across relevant views.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC014 — Verify product images
**Steps:**
1. Inspect the product images.
2. Check for missing or broken images.  
**Expected Result:** Product images should load and correspond to their displayed products.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC015 — Verify product descriptions
**Steps:**
1. Open a product details page, if available.
2. Review its description.  
**Expected Result:** The description should be readable and associated with the correct product.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC016 — Sort products by name ascending
**Steps:**
1. Select the name A-to-Z sorting option.
2. Compare the product names in sequence.  
**Expected Result:** Products should appear in ascending alphabetical order.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC017 — Sort products by name descending
**Steps:**
1. Select the name Z-to-A option.
2. Compare the product names.  
**Expected Result:** Products should appear in descending alphabetical order.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC018 — Sort products by price ascending
**Steps:**
1. Select price low-to-high sorting.
2. Compare the displayed prices.  
**Expected Result:** Products should appear from lowest to highest price.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC019 — Sort products by price descending
**Steps:**
1. Select price high-to-low sorting.
2. Compare the displayed prices.  
**Expected Result:** Products should appear from highest to lowest price.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC020 — Verify sorting after changing the sort option
**Steps:**
1. Apply one sorting option.
2. Select another sorting option.
3. Observe the product order.  
**Expected Result:** The list should update according to the newly selected option.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 5. Shopping Cart Testing

### TC021 — Add one product to cart
**Precondition:** User is logged in.  
**Steps:**
1. Select a product.
2. Click Add to Cart.
3. Observe the cart indicator.  
**Expected Result:** The selected product should be added, and the cart indicator should update if displayed.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC022 — Add multiple different products
**Steps:**
1. Add two different products.
2. Open the cart.  
**Expected Result:** Both products should appear in the cart.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC023 — Verify cart item count
**Steps:**
1. Add one product.
2. Record the cart count.
3. Add another product.
4. Observe the count again.  
**Expected Result:** The displayed count should reflect the number of selected items according to the application behavior.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC024 — Verify product details in cart
**Steps:**
1. Add a product to the cart.
2. Open the cart.
3. Compare its name, description, and price with the product listing.  
**Expected Result:** The cart should show the correct selected product details.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC025 — Remove a product from cart
**Precondition:** At least one product is in the cart.  
**Steps:**
1. Open the cart.
2. Click Remove for one product.  
**Expected Result:** The selected product should be removed.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC026 — Remove all selected products
**Steps:**
1. Add multiple products.
2. Remove each product from the cart.  
**Expected Result:** No selected products should remain in the cart.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC027 — Verify empty cart
**Steps:**
1. Ensure the cart contains no products.
2. Open the cart.  
**Expected Result:** No product items should be listed. The page should remain usable.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC028 — Navigate from products to cart
**Steps:**
1. Open the products page.
2. Click the cart icon.  
**Expected Result:** The cart page should open.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC029 — Continue shopping from cart
**Steps:**
1. Open the cart.
2. Click Continue Shopping, if available.  
**Expected Result:** User should return to the products page.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC030 — Verify cart state after navigation
**Steps:**
1. Add a product.
2. Navigate between the products page and cart.
3. Reopen the cart.  
**Expected Result:** Cart contents should behave consistently with the application's design.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 6. Checkout Testing

### TC031 — Start checkout with a product in cart
**Precondition:** User is logged in and the cart contains a product.  
**Steps:**
1. Open the cart.
2. Click Checkout.  
**Expected Result:** The checkout information page should open.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC032 — Continue checkout with valid information
**Test Data:** First name: `Test`; Last name: `User`; Postal code: `500001`  
**Steps:**
1. Enter the fictional test details.
2. Click Continue.  
**Expected Result:** User should proceed to the next checkout step.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC033 — Checkout with first name empty
**Test Data:** First name empty; other required fields completed.  
**Steps:**
1. Leave the first name blank.
2. Complete the other required fields.
3. Click Continue.  
**Expected Result:** The application should prevent continuation and display validation.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC034 — Checkout with last name empty
**Test Data:** Last name empty; other required fields completed.  
**Steps:**
1. Leave the last name blank.
2. Complete the other required fields.
3. Click Continue.  
**Expected Result:** Appropriate validation should be displayed.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC035 — Checkout with postal code empty
**Test Data:** Postal code empty; other required fields completed.  
**Steps:**
1. Leave the postal code blank.
2. Complete the other required fields.
3. Click Continue.  
**Expected Result:** Appropriate validation should be displayed.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC036 — Checkout with all fields empty
**Steps:**
1. Open the checkout information page.
2. Leave all required fields empty.
3. Click Continue.  
**Expected Result:** Checkout should not proceed, and validation should appear.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC037 — Checkout with leading and trailing spaces
**Test Data:** Enter fictional names with leading or trailing spaces.  
**Steps:**
1. Enter the test values.
2. Complete the other required fields.
3. Click Continue.  
**Expected Result:** Whitespace should be handled according to the application's validation rules.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC038 — Checkout with special characters
**Test Data:** Use a name such as `Test@User`.  
**Steps:**
1. Enter the special-character input in a name field.
2. Complete the other required fields.
3. Continue.  
**Expected Result:** Input should be handled safely according to the application's requirements.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC039 — Checkout with long input
**Steps:**
1. Enter a long fictional name.
2. Complete the other required fields.
3. Continue.  
**Expected Result:** The application should handle the input safely and consistently.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC040 — Return from checkout information page
**Steps:**
1. Open the checkout information page.
2. Click Cancel, if available.  
**Expected Result:** User should return to the appropriate previous page without unexpected errors.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 7. Order Summary and Completion Testing

### TC041 — Verify order summary products
**Precondition:** Checkout information has been submitted successfully.  
**Steps:**
1. Open the order summary.
2. Compare its products with the cart.  
**Expected Result:** The order summary should contain the selected products.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC042 — Verify order summary prices
**Steps:**
1. Record product prices in the cart.
2. Continue to the order summary.
3. Compare the prices.  
**Expected Result:** Displayed product prices should be consistent.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC043 — Verify subtotal calculation
**Steps:**
1. Select multiple products.
2. Record their displayed prices.
3. Calculate their sum.
4. Compare it with the displayed subtotal.  
**Expected Result:** The subtotal should equal the sum of the selected product prices.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC044 — Verify tax calculation
**Steps:**
1. Open the order summary.
2. Record the displayed subtotal and tax.
3. Check the total against the displayed values and application rules.  
**Expected Result:** Tax and total should be calculated consistently with the application's rules.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC045 — Verify final total
**Steps:**
1. Record subtotal and tax.
2. Calculate the expected final total.
3. Compare it with the displayed total.  
**Expected Result:** Final total should equal subtotal plus displayed tax, according to the application rules.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC046 — Complete the order
**Precondition:** User has reached the final checkout step.  
**Steps:**
1. Review the order summary.
2. Click the final order completion button.
3. Observe the resulting page.  
**Expected Result:** The application should display the appropriate order completion confirmation.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC047 — Verify order confirmation message
**Steps:**
1. Complete the supported checkout workflow.
2. Observe the confirmation page.  
**Expected Result:** A clear confirmation message should be displayed.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC048 — Verify cart after order completion
**Steps:**
1. Complete an order.
2. Navigate to the cart, if available.
3. Observe the cart contents.  
**Expected Result:** Cart state should match the application's intended post-order behavior.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 8. Navigation and Session Testing

### TC049 — Verify logout
**Precondition:** User is logged in.  
**Steps:**
1. Open the navigation menu.
2. Click Logout.  
**Expected Result:** User should be logged out and returned to the login page.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC050 — Verify access to a protected page after logout
**Steps:**
1. Log in.
2. Open a protected page.
3. Log out.
4. Try to revisit the protected page using navigation or the browser Back button.  
**Expected Result:** Protected content should not remain accessible to an unauthenticated user where authentication is required.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC051 — Verify session behavior after browser refresh
**Steps:**
1. Log in and open the products page.
2. Refresh the page.
3. Observe the resulting state.  
**Expected Result:** Behavior should match the application's session design without unexpected errors.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC052 — Verify browser Back navigation
**Steps:**
1. Navigate from products to cart.
2. Use the browser Back button.
3. Observe the displayed page and state.  
**Expected Result:** Navigation should work consistently without unexpected errors.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 9. UI, Usability, and Compatibility Testing

### TC053 — Verify button labels
**Steps:**
1. Inspect the login, products, cart, and checkout pages.
2. Review visible button labels.  
**Expected Result:** Buttons should have understandable and appropriate labels.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC054 — Verify keyboard navigation
**Steps:**
1. Use the Tab key to navigate through visible controls.
2. Use the appropriate keyboard controls to activate them.  
**Expected Result:** Important controls should be reachable and usable by keyboard.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC055 — Verify page readability
**Steps:**
1. Review headings, product names, prices, and messages.
2. Check whether content is readable and properly arranged.  
**Expected Result:** Text should be readable and the page should be understandable.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC056 — Verify layout at different window sizes
**Steps:**
1. Open the application in a desktop browser.
2. Resize the browser window.
3. Observe important controls and page layout.  
**Expected Result:** Important content should remain usable without unintended layout problems.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC057 — Verify cross-browser behavior
**Steps:**
1. Open the application in supported browsers.
2. Repeat selected login, cart, and checkout tests.
3. Compare the results.  
**Expected Result:** Core functionality should behave consistently across supported browsers.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 10. Negative Testing and Regression Testing

### TC058 — Verify repeated Add to Cart clicks
**Steps:**
1. Click Add to Cart for a product.
2. Observe the button and cart count.
3. Repeat only where the UI allows the action.  
**Expected Result:** The cart should behave according to the application's design without unintended duplicate items or inconsistent counts.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC059 — Verify handling of invalid workflow input
**Steps:**
1. Enter invalid or incomplete information in a relevant form.
2. Submit the form.
3. Observe the response.  
**Expected Result:** Invalid input should be handled safely, and appropriate validation should appear.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

### TC060 — Perform regression testing after a change
**Precondition:** A change or fix has been introduced in the test environment.  
**Steps:**
1. Identify the changed functionality.
2. Retest the affected test case.
3. Run related login, product, cart, and checkout tests.
4. Compare the results with the expected behavior.  
**Expected Result:** The fix should work, and related functionality should not be negatively affected.  
**Actual Result:** Not recorded.  
**Status:** Not Executed.

---

# 11. Test Execution Summary

| Metric           | Initial Value |

| Total Test Cases  | 60 |
| Executed          | 0 |
| Passed            | 0 |
| Failed            | 0 |
| Blocked           | 0 |
| Not Executed      | 60 |
| Confirmed Defects | 0 |

**Note:** These are initial values before execution. Zero confirmed defects does not mean the application is defect-free.

# 12. Test Execution Guidelines

1. Execute tests only against the practice application.
2. Record the actual observed result for each test.
3. Mark a test Pass only when actual and expected results match.
4. Mark a test Fail when the observed behavior differs from the expected result.
5. Reproduce failures before reporting them as confirmed defects.
6. Capture screenshots when they help demonstrate the result.
7. Use fictional data only; never use real payment or personal information.
8. Update the execution summary after testing.

## Final Status

**Documentation:** Prepared.

**Execution:** Pending actual manual testing.

**Defects:** No defects are claimed as confirmed until reproduced and documented.
