\# Equivalence Partitioning and Boundary Value Analysis — SauceDemo



\## 1. Equivalence Partitioning (EP)



\### Purpose



Equivalence Partitioning divides input data into groups expected to behave similarly. Instead of testing every possible value, a representative value from each group is selected.



\### Login Form



| Input    | Equivalence Class                | Example          | Expected Behavior                                     |

| -------- | -------------------------------- | ---------------- | ----------------------------------------------------- |

| Username | Valid registered username        | `standard\_user`  | Login succeeds when paired with the correct password. |

| Username | Invalid or unregistered username | `wrong\_username` | Login is rejected.                                    |

| Username | Empty value                      | Empty            | Login is rejected.                                    |

| Password | Valid password                   | `secret\_sauce`   | Login succeeds when paired with a valid username.     |

| Password | Invalid password                 | `wrong\_password` | Login is rejected.                                    |

| Password | Empty value                      | Empty            | Login is rejected.                                    |



These classes were used to design representative login tests.



\## 2. Boundary Value Analysis (BVA)



\### Purpose



Boundary Value Analysis focuses on values at the edges of a defined input range, where defects are more likely to occur.



\### Hypothetical Example



The following example is for learning purposes only. The limits below are hypothetical and are not confirmed SauceDemo requirements.



Assume a field accepts values from 8 to 24 characters, inclusive.



| Test Value    | Category           | Expected Result |

| ------------- | ------------------ | --------------- |

| 7 characters  | Just below minimum | Rejected        |

| 8 characters  | Minimum boundary   | Accepted        |

| 9 characters  | Just above minimum | Accepted        |

| 23 characters | Just below maximum | Accepted        |

| 24 characters | Maximum boundary   | Accepted        |

| 25 characters | Just above maximum | Rejected        |



\## 3. Important Distinction



The hypothetical 8–24 character range is not a verified rule for SauceDemo. TC-009 tests a 25-character incorrect password, but it does not prove that the application has a maximum password length of 24 characters.



For actual application testing, boundary values should be derived from documented requirements or verified constraints.



\## 4. Conclusion



Equivalence Partitioning helps reduce the number of test inputs by selecting representative values from meaningful classes.



Boundary Value Analysis concentrates on values around specified limits.



Both techniques support systematic test design and help identify gaps in test coverage.



