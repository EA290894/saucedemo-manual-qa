\# Test Cases — SauceDemo



\*\*Application:\*\* SauceDemo

\*\*URL:\*\* https://www.saucedemo.com/

\*\*Test Account:\*\* `standard\_user`

\*\*Password:\*\* `secret\_sauce`



\---



\## Login and Authentication



\### TC-001 — Login with valid credentials



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `standard\_user`; Password: `secret\_sauce`

\* \*\*Steps:\*\*



&#x20; 1. Enter a valid username.

&#x20; 2. Enter a valid password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* The user is redirected to the Products page.

\* \*\*Type:\*\* Positive



\### TC-002 — Login with invalid username and password



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `wrong\_user`; Password: `wrong\_password`

\* \*\*Steps:\*\*



&#x20; 1. Enter an invalid username.

&#x20; 2. Enter an invalid password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed, and the user remains on the Login page.

\* \*\*Type:\*\* Negative



\### TC-003 — Login with valid username and invalid password



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `standard\_user`; Password: `wrong\_password`

\* \*\*Steps:\*\*



&#x20; 1. Enter the valid username.

&#x20; 2. Enter an incorrect password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed, and the user remains on the Login page.

\* \*\*Type:\*\* Negative



\### TC-004 — Login with invalid username and valid password



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `wrong\_username`; Password: `secret\_sauce`

\* \*\*Steps:\*\*



&#x20; 1. Enter an unregistered username.

&#x20; 2. Enter the valid password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed, and the user remains on the Login page.

\* \*\*Type:\*\* Negative



\### TC-005 — Login with empty username



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: empty; Password: `secret\_sauce`

\* \*\*Steps:\*\*



&#x20; 1. Leave the username field empty.

&#x20; 2. Enter the password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed.

\* \*\*Type:\*\* Negative



\### TC-006 — Login with empty password



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `standard\_user`; Password: empty

\* \*\*Steps:\*\*



&#x20; 1. Enter the username.

&#x20; 2. Leave the password field empty.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed.

\* \*\*Type:\*\* Negative



\### TC-007 — Login with a one-character password



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `standard\_user`; Password: `G`

\* \*\*Steps:\*\*



&#x20; 1. Enter the username.

&#x20; 2. Enter `G` as the password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed.

\* \*\*Type:\*\* Negative



\### TC-008 — Login with both fields empty



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: empty; Password: empty

\* \*\*Steps:\*\*



&#x20; 1. Leave both fields empty.

&#x20; 2. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed.

\* \*\*Type:\*\* Negative



\### TC-009 — Login with a 25-character incorrect password



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `standard\_user`; Password: `0123456789012345678901234`

\* \*\*Steps:\*\*



&#x20; 1. Enter the username.

&#x20; 2. Enter the 25-character password.

&#x20; 3. Click Login.

\* \*\*Expected Result:\*\* An error message is displayed.

\* \*\*Type:\*\* Negative



\---



\## Product Catalog



\### TC-010 — Verify the Products page after login



\* \*\*Preconditions:\*\* User is on the Login page.

\* \*\*Test Data:\*\* Username: `standard\_user`; Password: `secret\_sauce`

\* \*\*Steps:\*\*



&#x20; 1. Log in with valid credentials.

\* \*\*Expected Result:\*\* The Products page is displayed.

\* \*\*Type:\*\* Positive



\### TC-011 — Verify that products are displayed



\* \*\*Preconditions:\*\* User is logged in.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Open the Products page.

&#x20; 2. Inspect the product catalog.

\* \*\*Expected Result:\*\* Products are displayed.

\* \*\*Type:\*\* Positive



\### TC-012 — Verify product names



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Inspect the product cards.

\* \*\*Expected Result:\*\* Each product has a name.

\* \*\*Type:\*\* Positive



\### TC-013 — Verify product prices



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Inspect the product cards.

\* \*\*Expected Result:\*\* Each product has a price.

\* \*\*Type:\*\* Positive



\### TC-014 — Verify product images



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Inspect the product cards.

\* \*\*Expected Result:\*\* Each product has an image.

\* \*\*Type:\*\* Positive



\### TC-015 — Verify Add to cart buttons



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Inspect the product cards.

\* \*\*Expected Result:\*\* Each product has an Add to cart button.

\* \*\*Type:\*\* Positive



\### TC-016 — Verify product names in the catalog



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Compare the displayed product names with their details pages.

\* \*\*Expected Result:\*\* Product names match between the catalog and details pages.

\* \*\*Type:\*\* Positive



\### TC-017 — Verify product prices in the catalog



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Open a product details page.

&#x20; 2. Compare its price with the price in the catalog.

\* \*\*Expected Result:\*\* The prices match.

\* \*\*Type:\*\* Positive



\### TC-018 — Verify product images in the catalog



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* N/A

\* \*\*Steps:\*\*



&#x20; 1. Inspect product images.

\* \*\*Expected Result:\*\* Product images are displayed.

\* \*\*Type:\*\* Positive



\### TC-019 — Open product details



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Click a product name.

\* \*\*Expected Result:\*\* The corresponding product details page opens.

\* \*\*Type:\*\* Positive



\### TC-020 — Verify the product name on the details page



\* \*\*Preconditions:\*\* A product details page is open.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Compare the product name with the name in the catalog.

\* \*\*Expected Result:\*\* The product name matches.

\* \*\*Type:\*\* Positive



\### TC-021 — Verify the product price on the details page



\* \*\*Preconditions:\*\* A product details page is open.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Compare the product price with the catalog price.

\* \*\*Expected Result:\*\* The prices match.

\* \*\*Type:\*\* Positive



\### TC-022 — Verify the product description



\* \*\*Preconditions:\*\* A product details page is open.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Inspect the product details.

\* \*\*Expected Result:\*\* A product description is displayed.

\* \*\*Type:\*\* Positive



\### TC-023 — Verify the product image on the details page



\* \*\*Preconditions:\*\* A product details page is open.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Inspect the product image.

\* \*\*Expected Result:\*\* The product image is displayed.

\* \*\*Type:\*\* Positive



\### TC-024 — Add a product from the details page



\* \*\*Preconditions:\*\* A product details page is open, and the cart is empty.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Click Add to cart.

\* \*\*Expected Result:\*\* The button changes to Remove, and the cart badge displays `1`.

\* \*\*Type:\*\* Positive



\### TC-025 — Add a product from the catalog



\* \*\*Preconditions:\*\* User is on the Products page, and the cart is empty.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Click Add to cart.

\* \*\*Expected Result:\*\* The product is added to the cart, and the cart badge displays `1`.

\* \*\*Type:\*\* Positive



\### TC-026 — Verify the selected product in the cart



\* \*\*Preconditions:\*\* A product has been added to the cart.

\* \*\*Test Data:\*\* Any product

\* \*\*Steps:\*\*



&#x20; 1. Open Your Cart.

\* \*\*Expected Result:\*\* The selected product appears in the cart.

\* \*\*Type:\*\* Positive



\### TC-027 — Sort products by name



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* Name (A to Z)

\* \*\*Steps:\*\*



&#x20; 1. Select Name (A to Z) from the sorting menu.

\* \*\*Expected Result:\*\* Products are displayed in alphabetical order.

\* \*\*Type:\*\* Positive



\### TC-028 — Sort products by price



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* Price (low to high)

\* \*\*Steps:\*\*



&#x20; 1. Select Price (low to high) from the sorting menu.

\* \*\*Expected Result:\*\* Products are displayed in ascending price order.

\* \*\*Type:\*\* Positive



\### TC-029 — Verify sorting by price in descending order



\* \*\*Preconditions:\*\* User is on the Products page.

\* \*\*Test Data:\*\* Price (high to low)

\* \*\*Steps:\*\*



&#x20; 1. Select Price (high to low) from the sorting menu.

\* \*\*Expected Result:\*\* Products are displayed in descending price order.

\* \*\*Type:\*\* Positive



