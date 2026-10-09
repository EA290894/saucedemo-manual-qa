\# Test Observations — SauceDemo



\## OBS-001: Zip/Postal Code Field Accepts Special Characters



\*\*Application:\*\* SauceDemo

\*\*Area:\*\* Checkout — Your Information

\*\*Status:\*\* Observation — Not a Confirmed Defect

\*\*Priority:\*\* Not Assigned



\### Description



During checkout testing, the Zip/Postal Code field accepted the value `!!!` and allowed the user to continue to the Overview page.



\### Preconditions



\* The user is logged in.

\* At least one product has been added to the cart.

\* The user has opened the checkout form.



\### Steps to Reproduce



1\. Open the shopping cart.

2\. Click Checkout.

3\. Enter a first name.

4\. Enter a last name.

5\. Enter `!!!` in the Zip/Postal Code field.

6\. Click Continue.



\### Actual Result



The application allows the user to proceed to the Overview page.



\### Expected Result



The expected behavior cannot be determined conclusively because the required format for the Zip/Postal Code field has not been established.



\### Conclusion



This observation is not classified as a confirmed defect. Further clarification of the field's validation requirements would be needed before determining whether the behavior is incorrect.



No confirmed defects were identified during the recorded testing activities.



