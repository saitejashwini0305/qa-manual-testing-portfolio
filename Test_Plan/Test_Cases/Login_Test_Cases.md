# Login Test Cases

## TC001 - Valid Login

Steps:
1. Enter valid username
2. Enter valid password
3. Click Login

Expected Result:
User should successfully login.

---

## TC002 - Invalid Password

Steps:
1. Enter valid username
2. Enter invalid password
3. Click Login

Expected Result:
Error message displayed.

---

## TC003 - Empty Username

Expected Result:
Validation message displayed.

---

## TC004 - Empty Password

Expected Result:
Validation message displayed.

---

## TC005 - Empty Username and Password

Expected Result:
Validation message displayed.

---

## TC006 - Locked User Login

Steps:
1. Enter locked_out_user
2. Enter valid password
3. Click Login

Expected Result:
Appropriate error message displayed.

---

## TC007 - Username With Leading Spaces

Steps:
1. Enter username with leading spaces
2. Enter valid password
3. Click Login

Expected Result:
System should handle input appropriately.

---

## TC008 - Password With Leading Spaces

Steps:
1. Enter valid username
2. Enter password with spaces
3. Click Login

Expected Result:
Login should fail.

---

## TC009 - Copy Paste Password

Steps:
1. Copy password
2. Paste into password field
3. Click Login

Expected Result:
Login should work successfully.

---

## TC010 - Logout Functionality

Steps:
1. Login successfully
2. Click menu
3. Click Logout

Expected Result:
User redirected to login page.
