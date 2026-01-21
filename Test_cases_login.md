# Exploratory Testing Analysis - Login Functionality

This project was created as part of my QA tester preparation. 
The goal was to practically test and analyze a web application login form.

## Testing Object
**URL:** https://the-internet.herokuapp.com/login  
**Feature:** Login Form

## Test Cases & Results (Exploratory Test)

| Scenario | Expected Result | Actual Result | Status |
| :--- | :--- | :--- | :--- |
| Successful Login | User should see a message: "You logged into a secure area!" | Success message displayed in green | ✅ Pass |
| Incorrect Password | System should display: "Your password is invalid!" | Error message displayed in red | ✅ Pass |
| Empty Credentials | System should deny access and show an error | Message "Your username is invalid!" displayed | ✅ Pass |
| Non-existing User | System should display an error message | Message "Your username is invalid!" displayed | ✅ Pass |

## What I have learned
* How to identify key elements on a web page.
* The difference between positive and negative testing.
* How to document test results clearly for other team members.
