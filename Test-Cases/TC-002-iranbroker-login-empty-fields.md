# Test Case: Verify validation message when login fields are empty

**ID:** TC-002-iranbroker-login-empty-fields  
**Feature:** Login page

## Pre-conditions
- User is on iranbroker.net login page.

## Test Steps
1. Open iranbroker.net
2. Click on login logo
3. Do not type anything on username field
4. Do not type anything on password field
5. Click on "ورود به حساب کاربری"

## Expected Result
- An error message should be displayed indicating that username and password are required.

## Actual Result
- An error message was displayed: "فرمت ایمیل یا شماره همراهتان صحیح نیست"

## Status
- Fail
