Test Plan: SauceDemo — UI Testing

1. Application Under Test
SauceDemo — https://www.saucedemo.com/
A demo e-commerce web app provided by Sauce Labs for QA practice.


2. Objective
Validate the functional correctness of the SauceDemo login module across
positive, negative, boundary, and exploratory scenarios, and document any
defects found with clear reproduction steps.


3. Scope
In scope (this round):
Login module — valid login, invalid/locked users, case-sensitive
credential handling, known problem-user UI behavior

Out of scope (future rounds):
-Inventory sorting/filtering
-Cart functionality
-Checkout flow


4. Test Approach
Type: Manual, black-box testing
Test techniques used:

Positive testing — valid credentials, expected happy path
Negative testing — invalid/locked credentials, wrong case
Boundary testing — edge-case inputs (e.g. empty fields, field limits)
Exploratory testing — timeboxed, session-based investigation of
unexpected behavior (e.g. problem_user)


5. Test Environment
Browser: Chrome (latest)
URL: https://www.saucedemo.com/
Access: Public, no account creation required — uses predefined
SauceDemo test accounts


6. Test Data / Users
USERNAME | PASSWORD
standard_user | secret_sauce
locked_out_user | secret_sauce
accountproblem_user | secret_sauce
Standard_user(capital S) | secret_sauce


7. Entry Criteria
SauceDemo application is accessible and responsive
Test cases have been written and reviewed
Jira project is set up for bug logging


8. Exit Criteria
All planned test cases for the login module have been executed
All discovered defects are logged in Jira with reproduction steps
Results are recorded in the test case spreadsheet (Actual Result, Status)


9. Risks & Assumptions
SauceDemo is a shared public demo environment — behavior is assumed
stable, but state/data could change without notice
No environment-specific config (staging/prod) — only one environment
exists to test against
Testing is manual only at this stage; no automated regression coverage
yet for this module