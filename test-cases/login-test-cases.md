# Login Test Cases

Project: QA Portfolio Project  
Module: Authentication  
Tester: Felipe Ignacio Cajas Maureira  

---

Test Case ID: TC-001  
Title: Successful login with valid credentials  

Preconditions:
User account exists in the system.

Test Steps:
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Login button

Expected Result:
User should be redirected to the dashboard.

Test Data:
Email: testuser@email.com
Password: Test123!

Priority: High  
Status: Passed

---

Test Case ID: TC-002  
Title: Login with incorrect password  

Preconditions:
User account exists.

Test Steps:
1. Open login page
2. Enter valid email
3. Enter incorrect password
4. Click Login

Expected Result:
System should display error message "Invalid credentials".

Priority: High  
Status: Passed

---

Test Case ID: TC-003  
Title: Login with empty fields  

Preconditions:
User is on login page.

Test Steps:
1. Leave email empty
2. Leave password empty
3. Click Login

Expected Result:
Validation messages should appear.

Priority: Medium  
Status: Passed

---

Test Case ID: TC-004  
Title: Login with invalid email format  

Preconditions:
User is on login page.

Test Steps:
1. Enter invalid email format
2. Enter password
3. Click Login

Expected Result:
System should display email format validation error.

Priority: Medium  
Status: Not Executed
