\# Checklists — SauceDemo



\## 1. Login Checklist



| ID           | Check                                                                  | Expected Result                          |

| ------------ | ---------------------------------------------------------------------- | ---------------------------------------- |

| CL-LOGIN-001 | Login with valid credentials                                           | User is redirected to the Products page. |

| CL-LOGIN-002 | Login with invalid username and password                               | An error message is displayed.           |

| CL-LOGIN-003 | Login with a registered username and invalid password                  | An error message is displayed.           |

| CL-LOGIN-004 | Login with an unregistered username and valid password                 | An error message is displayed.           |

| CL-LOGIN-005 | Login with an empty username and valid password                        | An error message is displayed.           |

| CL-LOGIN-006 | Login with a registered username and empty password                    | An error message is displayed.           |

| CL-LOGIN-007 | Login with a registered username and one-character password            | An error message is displayed.           |

| CL-LOGIN-008 | Login with both fields empty                                           | An error message is displayed.           |

| CL-LOGIN-009 | Login with a registered username and a 25-character incorrect password | An error message is displayed.           |



\## 2. Product Catalog Checklist



| ID         | Check                                           | Expected Result                                          |

| ---------- | ----------------------------------------------- | -------------------------------------------------------- |

| CL-CAT-001 | Verify the Products page after successful login | The Products page is displayed.                          |

| CL-CAT-002 | Verify that products are displayed              | Products are visible in the catalog.                     |

| CL-CAT-003 | Verify product names                            | Each product has a name.                                 |

| CL-CAT-004 | Verify product prices                           | Each product has a price.                                |

| CL-CAT-005 | Verify product images                           | Each product has an image.                               |

| CL-CAT-006 | Verify Add to cart buttons                      | Each product has an Add to cart button.                  |

| CL-CAT-007 | Verify product names in the catalog             | Product names are displayed correctly.                   |

| CL-CAT-008 | Verify product prices in the catalog            | Product prices are displayed correctly.                  |

| CL-CAT-009 | Verify product images in the catalog            | Product images are displayed correctly.                  |

| CL-CAT-010 | Click a product name                            | The product details page opens.                          |

| CL-CAT-011 | Verify the product name on the details page     | The correct product name is displayed.                   |

| CL-CAT-012 | Verify the product price on the details page    | The correct product price is displayed.                  |

| CL-CAT-013 | Verify the product description                  | The product description is displayed.                    |

| CL-CAT-014 | Verify the product image on the details page    | The product image is displayed.                          |

| CL-CAT-015 | Add a product to the cart from its details page | The product is added to the cart.                        |

| CL-CAT-016 | Add a product from the catalog                  | The product is added to the cart.                        |

| CL-CAT-017 | Verify the selected product in the cart         | The selected product appears in the cart.                |

| CL-CAT-018 | Sort products by name                           | Products are sorted by name.                             |

| CL-CAT-019 | Sort products by price                          | Products are sorted by price.                            |

| CL-CAT-020 | Verify the selected sorting order               | The displayed order matches the selected sorting option. |



