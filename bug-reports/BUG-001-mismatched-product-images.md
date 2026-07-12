# BUG-001: problem_user sees mismatched product images

**Jira Ticket:** SD-1 (https://irfanfaizchoo.atlassian.net/browse/SAUC-1)
**Test Case:** TC_LOGIN_003
**Severity:** Minor | 
**Priority:** Medium

## Steps to Reproduce
1. Go to https://www.saucedemo.com/
2. Login with `problem_user` / `secret_sauce`
3. Observe inventory page

## Expected
Each product shows its correct image.

## Actual
All products show the same dog image.

## Screenshot
![alt text](BUG-001-dog-img.png)