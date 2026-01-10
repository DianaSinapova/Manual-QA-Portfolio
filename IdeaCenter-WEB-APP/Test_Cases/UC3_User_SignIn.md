### Test Case ID:
UC3-1

### Title:
Verify that all required fields and buttons are present on the Sign In page

### Preconditions:
- User is registered and logged out

### Test Steps:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Observe that all input fields and buttons are present and correctly displayed.

### Expected Result:
The Sign In page provides the following:
- Email field
- Password field
- Remember Me checkbox
- Sign In button

### Actual Result:
Sign up options via Google or Facebook buttons are present on the Sign In page, which are not required.

### Status:
Fail

### Bug ID:
BUG-6


//////////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC3-2

### Title:
Verify that signing in with valid credentials is possible

### Preconditions:
- User is registered and logged out

### Test Steps:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Enter valid credentials in the Email and Password fields.
3. Check the "Remember Me" checkbox.
4. Click on the "Sign In" button.

### Expected Result:
User is successfully authenticated and redirected to the Home page for logged in users.

### Actual Result:
User is redirected to the Home page for logged in users.

### Status:
Pass

### Bug ID:
N/A


//////////////////////////////////////////////////////////////////////////////////////////////////



### Test Case ID:
UC3-3

### Title:
Verify that "Remember Me" functionality keeps the user logged in

### Preconditions:
- User is registered and logged out

### Test Steps:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Enter valid credentials in the Email and Password fields.
3. Check the "Remember Me" checkbox.
4. Click on the "Sign In" button.
5. Refresh the page or close and reopen the browser.

### Expected Result:
User remains logged in and is not required to sign in again.

### Actual Result:
User is prompted to sign in again after refreshing or reopening the browser.

### Status:
Fail

### Bug ID:
BUG-7


////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC3-4

### Title:
Verify that signing in with invalid credentials is not possible

### Preconditions:
- User is registered and logged out

### Test Steps:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Enter invalid credentials in the Email and/or Password fields.
3. Click on the "Sign In" button.

### Expected Result:
An error message is displayed indicating that the credentials are invalid.

### Actual Result:
An error message is displayed indicating that the credentials are invalid.

### Status:
Pass

### Bug ID:
N/A


///////////////////////////////////////////////////////////////////////////////////////////////


### Test Case ID:
UC3-5

### Title:
Verify that signing in with an empty Email field is not possible

### Preconditions:
- User is registered and logged out

### Test Steps:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Fill in all required fields except the Email field.
3. Click on the "Sign In" button.

### Expected Result:
An error message is displayed indicating that the Email field is required.

### Actual Result:
An error message is displayed indicating that the Email field is required.

### Status:
Pass

### Bug ID:
N/A


//////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC3-6

### Title:
Verify that signing in with an empty Password field is not possible

### Preconditions:
- User is registered and logged out

### Test Steps:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Fill in all required fields except the Password field.
3. Click on the "Sign In" button.

### Expected Result:
An error message is displayed indicating that the Password field is required.

### Actual Result:
An error message is displayed indicating that the Password field is required.

### Status:
Pass

### Bug ID:
N/A

