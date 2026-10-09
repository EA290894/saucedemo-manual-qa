\# QA Test Report — SauceDemo



\## 1. Project Information



\* \*\*Application:\*\* SauceDemo

\* \*\*Application URL:\*\* https://www.saucedemo.com/

\* \*\*Testing Type:\*\* Manual Functional Testing

\* \*\*Test Account:\*\* `standard\_user`

\* \*\*Test Period:\*\* October 2026

\* \*\*Test Environment:\*\* Windows 11; browser version not recorded



\## 2. Testing Scope



The following areas were tested:



\* Login and authentication

\* Product catalog and product details

\* Product sorting

\* Shopping cart functionality

\* Checkout form validation

\* Checkout navigation

\* Price calculation

\* Order completion

\* Logout and access restrictions



\## 3. Testing Activities



The project includes the following testing activities and documentation:



\* Test scenario design

\* Checklist creation

\* Test case design

\* Positive and negative testing

\* Equivalence Partitioning (EP)

\* Boundary Value Analysis (BVA)

\* Manual test execution

\* Test result documentation

\* Observation recording



\## 4. Test Execution Summary



The recorded functional checks completed during the project passed according to their expected results.



The checks covered product sorting, adding and removing products, cart updates, checkout validation, order overview, price calculations, order completion, and access restrictions after logout.



\## 5. Observations and Defects



No confirmed defects were identified within the tested scenarios.



One observation was documented:



\*\*OBS-001 — Zip/Postal Code Validation\*\*



The checkout form accepted `!!!` in the Zip/Postal Code field and allowed the user to continue to the Overview page. Because the expected input format was not established, this observation was not classified as a confirmed defect.



\## 6. Retesting and Regression Testing



\* \*\*Retesting:\*\* Not applicable because no confirmed defects were fixed.

\* \*\*Regression Testing:\*\* A full regression cycle after application changes was not performed because no application changes were made.



Additional functional checks were recorded as test execution results and were not classified as a full regression cycle.



\## 7. Conclusion



The project provided practical experience in manual functional testing, test documentation, test design techniques, and recording test observations.



No confirmed defects were found within the tested scope. The Zip/Postal Code validation observation remains unresolved pending clarification of the expected behavior.



\## 8. Limitations



\* The browser name and version were not recorded.

\* Testing was limited to the scenarios and checks documented in this project.

\* The application’s undocumented validation requirements were not treated as confirmed requirements.



