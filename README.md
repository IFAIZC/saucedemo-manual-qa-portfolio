# SauceDemo Manual QA Portfolio

Manual testing project on [SauceDemo](https://www.saucedemo.com/), built to
demonstrate practical QA skills: test planning, test case design, bug
reporting, and exploratory testing — as part of my transition into a
QA Engineer role.

## 🐛 Highlight: Bug Found
## BUG-001
While testing the login module with SauceDemo's `problem_user` account,
found that **all products display the same (incorrect) image** on the
inventory page instead of their actual product images.

- **Test case:** `TC_LOGIN_003`
- **Severity:** Minor | **Status:** Failed

## BUG-002
While testing the cart module with the `standard_user` account, founded 
that **it by pass the user address input and went straight to payment confirmation page** without any inputs.

- **Test case:** `TC_CART_005`
- **Severity:** Major | **Status:** Failed

Full repro steps in [`bug-reports/`](./bug-reports/).

## 📋 What's in this repo

| Folder/File | Description |
|---|---|
| [`test-plan.md`](./test-plan.md) | Scope, approach, test data, entry/exit criteria |
| [`test-cases/`](./test-cases/) | Test cases covering login module (positive, negative, boundary) |
| [`bug-reports/`](./bug-reports/) | Detailed bug write-ups with repro steps and screenshots |
| [`exploratory-notes/`](./exploratory-notes/) | Session-based exploratory testing charters and notes |

## 🧪 Testing Approach
Manual, black-box testing covering:
- **Positive testing** — valid login, expected happy path
- **Negative testing** — invalid credentials, locked accounts, wrong case
- **Boundary testing** — edge-case field inputs
- **Exploratory testing** — timeboxed sessions targeting known problem areas

See [`test-plan.md`](./test-plan.md) for full details.

## 🛠️ Tools Used
- **Jira** — bug tracking
- **Google Sheets** — test case design and execution tracking
- **Git/GitHub** — version control and portfolio hosting

## 🔗 Related Work
Also building automated coverage of this same app using Playwright and the
Page Object Model — see [github.com/IFAIZC](https://github.com/IFAIZC)
for that repo.

## 👤 About
Irfan Faiz Choo, loves riding my sportbike — transitioning into QA Engineering, self-taught. Background in front-end development (Next.js, TailwindCSS) and hands-on QA process from working in a top dental clinic operations environment.