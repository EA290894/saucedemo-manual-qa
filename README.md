# SauceDemo — Manual QA Testing Project

## About the Project

This is a personal portfolio project demonstrating practical knowledge of manual software testing through functional testing of the SauceDemo web application.

**Application:** [SauceDemo](https://www.saucedemo.com/)
**Testing Type:** Manual Functional Testing
**Project Status:** Completed initial test documentation and execution activities

## Project Objectives

* Practice test scenario and test case design.
* Apply positive and negative testing.
* Understand Equivalence Partitioning (EP) and Boundary Value Analysis (BVA).
* Execute functional checks and record actual results.
* Document observations without making unsupported defect claims.
* Prepare structured QA documentation for a testing portfolio.

## Scope of Testing

* Login and authentication
* Product catalog and product details
* Product sorting
* Shopping cart functionality
* Checkout form validation
* Price calculation
* Order completion
* Navigation and access restrictions

## Project Structure

| Folder / File                                | Description                                          |
| -------------------------------------------- | ---------------------------------------------------- |
| `test-documentation/test-scenarios.md`       | High-level test scenarios                            |
| `test-documentation/checklists.md`           | Functional testing checklists                        |
| `test-documentation/test-cases.md`           | Detailed test cases                                  |
| `test-documentation/test-results.md`         | Recorded test execution results                      |
| `test-analysis/positive-negative-testing.md` | Positive and negative testing examples               |
| `test-analysis/ep-bva.md`                    | Equivalence Partitioning and Boundary Value Analysis |
| `bug-reports/observations.md`                | Documented test observation                          |
| `reports/qa-test-report.md`                  | Summary of testing activities and results            |

## Test Results

The recorded checks covered product sorting, cart operations, checkout validation, price calculations, order completion, and access restrictions.

No confirmed defects were identified within the tested scenarios.

One observation was recorded: the Zip/Postal Code field accepted `!!!` and allowed checkout to continue. Since the expected input format was not established, this was documented as an observation rather than a confirmed defect.

## Tools and Techniques

* Manual Functional Testing
* Test Scenario Design
* Test Case Design
* Checklist-Based Testing
* Positive and Negative Testing
* Equivalence Partitioning (EP)
* Boundary Value Analysis (BVA)
* Git and GitHub
* Markdown Documentation

## Project Limitations

* Testing was limited to the documented scenarios and recorded checks.
* Browser name and version were not recorded.
* Full regression testing after application changes was not performed.
* The hypothetical input boundaries in the BVA example are not confirmed SauceDemo requirements.

## Author

**Eduard Aghajanyan**
Manual QA Trainee
