\# Positive and Negative Testing — SauceDemo



\## 1. Purpose



Positive testing verifies that an application behaves as expected when valid inputs and normal usage conditions are provided.



Negative testing verifies how an application handles invalid inputs, missing data, and unexpected user actions.



\## 2. Positive Test Cases



Positive testing focuses on expected application behavior under valid conditions.



| Test Case | Scenario                             | Expected Result                            |

| --------- | ------------------------------------ | ------------------------------------------ |

| TC-001    | Login with valid credentials         | Products page opens.                       |

| TC-010    | Verify Products page after login     | Products page is displayed.                |

| TC-011    | Verify products are displayed        | Products are visible.                      |

| TC-012    | Verify product names                 | Each product has a name.                   |

| TC-013    | Verify product prices                | Each product has a price.                  |

| TC-014    | Verify product images                | Product images are displayed.              |

| TC-015    | Verify Add to cart buttons           | Buttons are available.                     |

| TC-016    | Compare product names                | Names match between catalog and details.   |

| TC-017    | Compare product prices               | Prices match between catalog and details.  |

| TC-018    | Verify product images                | Images are displayed.                      |

| TC-019    | Open product details                 | Details page opens.                        |

| TC-020    | Verify product name on details page  | Name matches the selected product.         |

| TC-021    | Verify product price on details page | Price matches the catalog.                 |

| TC-022    | Verify product description           | Description is displayed.                  |

| TC-023    | Verify product image on details page | Image is displayed.                        |

| TC-024    | Add product from details page        | Product is added to cart.                  |

| TC-025    | Add product from catalog             | Product is added to cart.                  |

| TC-026    | Verify selected product in cart      | Selected product appears in cart.          |

| TC-027    | Sort products by name                | Products appear in alphabetical order.     |

| TC-028    | Sort products by price               | Products appear in ascending price order.  |

| TC-029    | Sort products by descending price    | Products appear in descending price order. |



\## 3. Negative Test Cases



Negative testing focuses on invalid credentials and missing required login information.



| Test Case | Scenario                            | Expected Result           |

| --------- | ----------------------------------- | ------------------------- |

| TC-002    | Invalid username and password       | Login error is displayed. |

| TC-003    | Valid username and invalid password | Login error is displayed. |

| TC-004    | Invalid username and valid password | Login error is displayed. |

| TC-005    | Empty username                      | Login error is displayed. |

| TC-006    | Empty password                      | Login error is displayed. |

| TC-007    | One-character incorrect password    | Login error is displayed. |

| TC-008    | Both login fields empty             | Login error is displayed. |

| TC-009    | 25-character incorrect password     | Login error is displayed. |



\## 4. Notes



\* Positive and negative testing describe the intent of a test, not whether the test passed or failed.

\* A negative test can pass when the application correctly rejects invalid input.

\* TC-009 checks an incorrect password; it does not establish a maximum password length.

\* Checkout validation checks are also negative tests, but they are not included in the login test-case numbering above.



