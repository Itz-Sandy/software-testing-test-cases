# Software Testing Test Cases

## Application Under Test
Sauce Demo Login Module

## Objective
To verify the functionality, validation, and usability of the login feature using positive, negative, and edge test scenarios.

| TC ID | Test Case | Steps | Expected Result | Actual Result | Severity |
|-------|-----------|--------|----------------|--------------|----------|
| TC-001 | Login with valid credentials | Enter valid username and password, then click Login | User should successfully log in | Not Executed | High |
| TC-002 | Login with invalid password | Enter valid username and invalid password | Error message should be displayed | Not Executed | High |
| TC-003 | Login with invalid username | Enter invalid username and valid password | Error message should be displayed | Not Executed | High |
| TC-004 | Login with both fields blank | Leave username and password blank and click Login | Validation/error message should appear | Not Executed | High |
| TC-005 | Login with blank username | Leave username blank and enter password | Username validation message should appear | Not Executed | High |
| TC-006 | Login with blank password | Enter username and leave password blank | Password validation message should appear | Not Executed | High |
| TC-007 | Username with leading spaces | Enter username with spaces before text | System should handle input correctly | Not Executed | Medium |
| TC-008 | Username with trailing spaces | Enter username with spaces after text | System should handle input correctly | Not Executed | Medium |
| TC-009 | Password field masking | Enter password in password field | Password should be masked | Not Executed | Medium |
| TC-010 | Login using Enter key | Enter credentials and press Enter | User should be logged in | Not Executed | Medium |
| TC-011 | Login with locked account | Use locked user credentials | Appropriate error message should appear | Not Executed | High |
| TC-012 | Username with special characters | Enter special characters in username field | Error message should appear | Not Executed | Medium |
| TC-013 | Password with special characters | Enter special characters as password | Error message should appear | Not Executed | Medium |
| TC-014 | Copy and paste password | Paste password into password field | Password should be accepted and masked | Not Executed | Low |
| TC-015 | Maximum username length | Enter a very long username | Application should handle input properly | Not Executed | Medium |
| TC-016 | Maximum password length | Enter a very long password | Application should handle input properly | Not Executed | Medium |
| TC-017 | Refresh login page | Refresh the browser on login page | Login page should reload correctly | Not Executed | Low |
| TC-018 | Logout functionality | Login and click Logout | User should be logged out successfully | Not Executed | High |
| TC-019 | Access protected page after logout | Logout and use browser Back button | Protected page should not be accessible | Not Executed | High |
| TC-020 | Multiple failed login attempts | Attempt login with wrong credentials multiple times | Error messages should be displayed consistently | Not Executed | Medium |

## Conclusion
The above test cases cover positive, negative, and edge scenarios for the Sauce Demo Login Module and help ensure the reliability and quality of the application.
