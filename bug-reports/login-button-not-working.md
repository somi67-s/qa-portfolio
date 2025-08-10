Bug Report – Login Button Not Working (Web Application)

Bug ID: BR-001
Title: Login button is not clickable after entering valid credentials on Chrome 124
Reported by: Somaye Soodmand
Date: 2025-08-10
Severity: Major
Priority: High
Environment:

    Device: Desktop

    OS: Windows 10

    Browser: Chrome 124.0.6367.91

    URL: https://example.com/login

Preconditions

    User has a valid account (test@example.com / Test@1234)

    User is on the Login page and not authenticated.

Steps to Reproduce

    Navigate to the login page.

    Enter test@example.com in the Email field.

    Enter Test@1234 in the Password field.

    Click the Login button.

Expected Result

    User is redirected to the dashboard page within 2–3 seconds.

Actual Result

    Login button shows a loading spinner for ~1 second, then returns to idle state and nothing happens.

    No error message is displayed.

Evidence

    Screenshot: login_button_not_working.png

    Video: login_button_issue.mp4

    Console log (optional): TypeError: Cannot read properties of undefined (reading 'token')

Notes

    Issue occurs consistently (5/5 attempts).

    Works as expected in Firefox 126
