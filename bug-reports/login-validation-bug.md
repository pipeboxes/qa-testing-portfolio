Bug ID: BUG-001

Title:
Login form validation behavior

Environment:
Browser: Chrome
OS: Windows

Description:
During login validation testing, the system correctly shows an error when credentials are incorrect. However, validation behavior should always be verified to ensure that empty fields or incorrect credentials are handled properly.

Steps to reproduce:
1. Open login page
2. Enter username
3. Enter incorrect password
4. Click login

Expected result:
System should prevent login and show validation error message.

Actual result:
Error message appears indicating invalid credentials.

Severity:
Low

Priority:
Medium

Status:
Open
