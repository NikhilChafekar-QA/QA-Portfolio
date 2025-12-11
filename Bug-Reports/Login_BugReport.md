Bug Report – Login Validation Issue

Bug ID: BUG_LOGIN_01
Module: Login
Severity: High
Priority: High
Reported By: Nikhil Chafekar
Environment: Chrome 120, Windows 10

Summary

The login page accepts an email without the @ symbol and proceeds with the login attempt instead of validating the input.

Steps to Reproduce

Navigate to: https://www.example.com/login

Enter email: nikhil123

Enter a valid password

Click Login

Expected Result

The system should prevent submission and display an inline validation message:
“Enter valid email address.”

Actual Result

The system accepts the invalid email and attempts to authenticate the user.
