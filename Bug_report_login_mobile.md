# Bug Report: Login button not responsive on iPhone 15

**Bug ID:** BUG-001  
**Severity:** Critical  
**Priority:** High  
**Status:** Open  

## Description
The "Login" button does not trigger any action when tapped on mobile Safari (iPhone 15). The user fills in valid credentials, but the form is not submitted.

## Steps to Reproduce
1. Open Safari on iPhone 15.
2. Navigate to https://the-internet.herokuapp.com/login
3. Enter username: `tomsmith`
4. Enter password: `SuperSecretPassword!`
5. Tap the "Login" button.

## Expected Result
The user should be redirected to the secure area page.

## Actual Result
Nothing happens. The button changes color on tap, but no request is sent and the page remains the same.

## Environment
* **Device:** iPhone 15
* **OS:** iOS 17.2
* **Browser:** Safari
