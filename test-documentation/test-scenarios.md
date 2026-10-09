\# Test Scenarios — SauceDemo



\## 1. Login and Authentication



\* TS-001: Verify login with valid credentials.

\* TS-002: Verify login with invalid credentials.

\* TS-003: Verify login with an empty username.

\* TS-004: Verify login with an empty password.

\* TS-005: Verify login with both fields empty.

\* TS-006: Verify login with an invalid password for a registered username.



\## 2. Product Catalog



\* TS-007: Verify that the Products page is displayed after successful login.

\* TS-008: Verify that products are displayed in the catalog.

\* TS-009: Verify that each product has a name, price, image, and Add to cart button.

\* TS-010: Verify that clicking a product opens its details page.

\* TS-011: Verify that product details are displayed correctly.

\* TS-012: Verify product sorting by name.

\* TS-013: Verify product sorting by price.



\## 3. Shopping Cart



\* TS-014: Verify that a product can be added to the cart from the catalog.

\* TS-015: Verify that a product can be added to the cart from its details page.

\* TS-016: Verify that added products appear in the cart.

\* TS-017: Verify that multiple products can be added to the cart.

\* TS-018: Verify that a product can be removed from the cart.

\* TS-019: Verify that the cart badge updates after adding or removing products.

\* TS-020: Verify that cart contents persist when navigating between the catalog and product details.



\## 4. Checkout



\* TS-021: Verify that checkout cannot continue when required fields are empty.

\* TS-022: Verify validation of the First Name field.

\* TS-023: Verify validation of the Last Name field.

\* TS-024: Verify validation of the Zip/Postal Code field.

\* TS-025: Verify that checkout proceeds when all required fields are filled.

\* TS-026: Verify that product prices are displayed correctly in the order overview.

\* TS-027: Verify that the item total and final total are calculated correctly.

\* TS-028: Verify that an order can be completed successfully.

\* TS-029: Verify that the cart is empty after completing an order and returning to the catalog.



\## 5. Navigation and Session



\* TS-030: Verify navigation from product details back to the catalog.

\* TS-031: Verify that the cart is accessible only when logged in.

\* TS-032: Verify that logout returns the user to the login page.

\* TS-033: Verify access restrictions after logout.



