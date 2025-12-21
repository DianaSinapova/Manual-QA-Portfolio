### Test Case ID:
UC2-1

### Title:
Verify that all input fields and buttons are present on the Sign Up page

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Observe all input fields and buttons on the Sign Up page.

### Expected Result:
The Sign Up page contains the following:
- Username field
- Email field
- Password field
- Repeat Password field
- Checkbox for agreeing to Terms of Service
- Register button
- Alternative sign up options via Google or Facebook buttons

### Actual Result:
Alternative sign up options via Google or Facebook buttons are missing on the Sign Up page.

### Status:
Fail

### Bug ID:
BUG-5


////////////////////////////////////////////////////////////////////////////////////////////////



### Test Case ID:
UC2-2

### Title:
Verify that the Terms of Service checkbox and hyperlink are present and available on the Sign Up page

### Preconditions:
- User is not logged in

### Test Steps:
1. Click on the "SIGN UP FOR FREE" button.
2. Observe that the checkbox for agreeing to the Terms of Service and the hyperlink to view the full Terms of Service document are present and available.

### Expected Result:
The Sign Up form includes:
- Checkbox for agreeing to the Terms of Service
- Hyperlink to view the full Terms of Service document

### Actual Result:
All elements are present and functional, matching the expected result.

### Status:
Pass

### Bug ID:
N/A


///////////////////////////////////////////////////////////////////////////////////////////////



### Test Case ID:
UC2-3

### Title:
Verify Sign Up functionality with valid data

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Fill in all required fields with valid data.
4. Click on the "REGISTER" button.

### Expected Result:
User is redirected to the Home page for registered users and is logged in automatically.

### Actual Result:
User is successfully redirected to the Home page, matching the expected result.

### Status:
Pass

### Bug ID:
N/A


////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC2-4

### Title:
Verify Username field limit with 31 characters

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Fill the Username field with 31 characters: "aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa".

### Expected Result:
The Username field does not allow more than 30 characters; input is truncated to 30 characters.

### Actual Result:
The Username field truncates input to 30 characters, matching the expected result.

### Status:
Pass

### Bug ID:
N/A


/////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC2-5

### Title:
Verify Sign Up with empty Username field is not allowed

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Fill all fields except the Username field.
4. Click on the "REGISTER" button.

### Expected Result:
An error message is displayed indicating that the Username field cannot be empty.

### Actual Result:
Error message is displayed as expected, matching the expected result.

### Status:
Pass

### Bug ID:
N/A


///////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC2-6

### Title:
Verify Sign Up with invalid Email format is not allowed

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Fill all fields with valid data but enter an invalid Email format (test@com).
4. Click on the "REGISTER" button.

### Expected Result:
A warning message is displayed indicating that the Email format is incorrect.

### Actual Result:
Warning message is displayed as expected, matching the expected result.

### Status:
Pass

### Bug ID:
N/A


///////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC2-7

### Title:
Verify Sign Up with empty Email field is not allowed

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Fill all fields with valid data except the Email field.
4. Click on the "REGISTER" button.

### Expected Result:
An error message is displayed indicating that the Email field cannot be empty.

### Actual Result:
Warning message is displayed as expected, matching the expected result.

### Status:
Pass

### Bug ID:
N/A


////////////////////////////////////////////////////////////////////////////////////////



### Test Case ID:
UC2-8

### Title:
Verify Sign Up with empty Password and Repeat Password fields is not allowed

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on the "SIGN UP FOR FREE" button.
3. Fill all fields with valid data, leaving the Password and Repeat Password fields empty.
4. Click on the "REGISTER" button.

### Expected Result:
An error message is displayed indicating that the Password and Repeat Password fields cannot be empty.

### Actual Result:
Warning message is displayed as expected, matching the expected result.

### Status:
Pass

### Bug ID:
N/A





