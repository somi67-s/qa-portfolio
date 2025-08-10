Test Case – Login Page (Web Application)

Test Case ID: TC-001
Title: Verify successful login with valid credentials
Module: Authentication – Login
Priority: High
Test Type: Functional – Positive
Prepared by: Somaye Soodmand
Date: 2025-08-10
Preconditions

    User has a valid account:
    Email: test@example.com
    Password: Test@1234

    User is on the Login page.

    Browser: Chrome 124.0.6367.91

    OS: Windows 10

Test Steps

    Navigate to the login page at https://example.com/login

    Enter valid email in the Email field.

    Enter valid password in the Password field.

    Click the Login button.

Expected Result

    User is redirected to the Dashboard page within 2–3 seconds.

    A welcome message with the user’s name is displayed.

Postconditions

    User is logged in and session is active.

Notes

    This case verifies the happy path for login.

    Further negative test cases should be created for invalid credentials, empty fields, and locked accounts
