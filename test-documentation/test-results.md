\# Test Execution Results — SauceDemo



\## 1. Test Environment



Application: SauceDemo

URL: https://www.saucedemo.com/

Test type: Manual Testing

Test account: `standard\_user`

Password: `secret\_sauce`

Browser and version: Not recorded

Execution date: October 2026



\## 2. Recorded Test Results



| ID        | Test Area           | Check                                          | Actual Result                                                      | Status |

| --------- | ------------------- | ---------------------------------------------- | ------------------------------------------------------------------ | ------ |

| CHECK-001 | Product Sorting     | Sort by Name (A to Z)                          | Products appeared in alphabetical order.                           | Passed |

| CHECK-002 | Product Sorting     | Sort by Price (low to high)                    | Prices appeared in ascending order.                                | Passed |

| CHECK-003 | Product Sorting     | Sort by Price (high to low)                    | Prices appeared in descending order.                               | Passed |

| CHECK-004 | Shopping Cart       | Add one product                                | Cart badge displayed 1.                                            | Passed |

| CHECK-005 | Shopping Cart       | Verify selected product in cart                | Selected product appeared in the cart.                             | Passed |

| CHECK-006 | Shopping Cart       | Remove product from cart                       | Product was removed.                                               | Passed |

| CHECK-007 | Shopping Cart       | Add two different products                     | Both products appeared, and the badge displayed 2.                 | Passed |

| CHECK-008 | Checkout Validation | Submit all fields empty                        | An error appeared, and checkout did not continue.                  | Passed |

| CHECK-009 | Checkout Validation | Leave Last Name and Zip/Postal Code empty      | Error identified Last Name as required.                            | Passed |

| CHECK-010 | Checkout Validation | Leave Zip/Postal Code empty                    | Error identified Zip/Postal Code as required.                      | Passed |

| CHECK-011 | Checkout            | Submit valid information                       | Checkout Overview opened and displayed both products.              | Passed |

| CHECK-012 | Price Validation    | Compare overview prices with catalog           | Product prices matched.                                            | Passed |

| CHECK-013 | Price Calculation   | Check item total and final total               | Calculations matched the expected values.                          | Passed |

| CHECK-014 | Checkout Completion | Finish the order                               | Order confirmation appeared.                                       | Passed |

| CHECK-015 | Shopping Cart       | Return Home after order completion             | Products page opened with an empty cart.                           | Passed |

| CHECK-016 | Checkout Navigation | Cancel from Your Information                   | Returned to cart, and the product remained.                        | Passed |

| CHECK-017 | Checkout Navigation | Cancel from Overview                           | Returned to Products, and the product remained in the cart.        | Passed |

| CHECK-018 | Shopping Cart       | Remove product from Products page              | Button changed to Add to cart, and the badge disappeared.          | Passed |

| CHECK-019 | Product Details     | Add product from details page                  | Button changed to Remove, and badge displayed 1.                   | Passed |

| CHECK-020 | Navigation          | Return from Product Details                    | Returned to Products without another login prompt on repeat check. | Passed |

| CHECK-021 | Product Details     | Remove product from details page               | Button changed to Add to cart, and badge disappeared.              | Passed |

| CHECK-022 | Shopping Cart       | Navigate back to Products                      | Product remained in cart, and badge displayed 1.                   | Passed |

| CHECK-023 | Shopping Cart       | Add a second product                           | Badge displayed 2, and both products appeared in the cart.         | Passed |

| CHECK-024 | Shopping Cart       | Remove one of two products                     | Badge displayed 1, and the other product remained.                 | Passed |

| CHECK-025 | Checkout Validation | Submit empty checkout form again               | Error indicated that First Name was required.                      | Passed |

| CHECK-026 | Authentication      | Access cart after logout                       | Site displayed a message that login was required.                  | Passed |

| CHECK-027 | Checkout Completion | Finish order after Zip/Postal Code observation | Order confirmation appeared.                                       | Passed |



\## 3. Observation



\*\*OBS-001 — Zip/Postal Code Validation\*\*



Input: `!!!`



Actual result: The application allowed checkout to continue to the Overview page.



Status: Observation — not classified as a confirmed defect because the expected format for Zip/Postal Code was not documented.



\## 4. Summary



The recorded checks passed according to their expected results.



No confirmed defects were identified within the tested scenarios. One validation observation remains unresolved.



Retesting of fixed defects was not applicable because no confirmed defects were fixed. Regression testing after application changes was not performed.



