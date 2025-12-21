### Bug ID: 1

Test Case ID:
UC1-1

### Title: 
Swapped places button on Navbar on Home page for not logged users


### Environment:

- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions: - User is not logged in

### Steps to Reproduce:
1. Open the application using the URL.
2. Observe the Navbar and check if all buttons are in the correct positions.

### Expected Result:
All buttons in the Navbar are in the correct positions:
- "SIGN IN" and "SIGN UP FOR FREE" buttons on the left
- "Back to Home page" link on the right

### Actual Result:
The buttons are swapped:
- "SIGN IN" and "SIGN UP FOR FREE" buttons are on the right
- "Back to Home page" link is on the left

### Severity:
Low

### Priority:
Low

### Status:
New


//////////////////////////////////////////////////////////////////////////////////////



### Bug ID: 2

### Test Case ID:
UC1-2

### Title:
Syntax error on carousel text on Home page for not logged users

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is not logged in

### Steps to Reproduce:
1. Open the application using the provided URL.
2. Observe the carousel slides and check the text on each slide.

### Expected Result:
The carousel text on the third slide should be:
- "Enjoy our site!"

### Actual Result:
The third slide contains a typo:
- "Enjoy out site!" instead of "Enjoy our site!"

### Severity:
Low

### Priority:
Low

### Status:
New


////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////



### Bug ID:
BUG-3

### Related Test Case:
UC1-4

### Title:
Incorrect call-to-action button text on carousel for not logged users

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is not logged in

### Steps to Reproduce:
1. Open the application using the provided URL.
2. Observe the call-to-action buttons on the carousel slides.

### Expected Result:
Two of the carousel slides contain call-to-action buttons with text:
- "SIGN UP FOR FREE"
- "SIGN IN"

### Actual Result:
One of the carousel slides displays a button with text:
"Register now" instead of "SIGN UP FOR FREE".

### Severity:
Low

### Priority:
Low

### Status:
New


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////




### Bug ID:
BUG-4

### Related Test Case:
UC1-5

### Title:
"Log In" button on Navbar does not redirect to Log In page

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is not logged in

### Steps to Reproduce:
1. Open the application using the provided URL.
2. Click on the "Log In" button in the Navbar.

### Expected Result:
User is redirected to the Log In page.

### Actual Result:
User remains on the Home page and no redirection occurs.

### Severity:
Medium

### Priority:
Medium

### Status:
New


////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////



### Bug ID: 
BUG-5

### Test Case ID:
UC2-1

### Title: 
Alternative sign up options via Google or Facebook buttons are missing on Sign Up page

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is not logged in

### Steps to Reproduce:
1. Click on the "SIGN UP FOR FREE" button.
2. Observe that all input fields and buttons are present on the Sign Up page.

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

### Severity:
Low

### Priority:
Low

### Status:
New

///////////////////////////////////////////////////////////////////////////////////////////////


### Bug ID: 
BUG-6

### Test Case ID:
UC3-1

### Title:
Extra Google and Facebook sign-up buttons are displayed on the Sign In page

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is not logged in

### Steps to Reproduce:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Observe all fields and buttons on the Sign In page.

### Expected Result:
The page provides fields for Email and Password, a "Remember password" checkbox, and a Sign In button.  
No Google or Facebook sign-up buttons should be displayed.

### Actual Result:
Extra Google and Facebook sign-up buttons are displayed on the Sign In page.

### Severity:
Low

### Priority:
Low

### Status:
New

///////////////////////////////////////////////////////////////////////////////////////////////////

### Bug ID: 
BUG-7

### Test Case ID:
UC3-3

### Title:
"Remember password" option on Sign In page does not work

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is not logged in

### Steps to Reproduce:
1. Click on the "Sign In" button on the Home page for logged out users.
2. Type valid credentials in the fields.
3. Check the "Remember password" checkbox.
4. Sign out and return to the Sign In page.

### Expected Result:
The password field is automatically filled with the previously entered password.

### Actual Result:
The password field does not support automatic filling; the "Remember password" option does not work.

### Severity:
Low

### Priority:
Low

### Status:
New

//////////////////////////////////////////////////////////////////////////////////

### Bug ID: 
BUG-8

### Test Case ID:
UC4-5

### Title:
Idea counter on My Profile page does not update correctly after creating a new idea

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is logged in

### Steps to Reproduce:
1. Click on the "Create New Idea" button.
2. Fill in all required fields to create a new idea.
3. Click on the "CREATE" button.
4. Click on the "My Profile" button.
5. Observe whether the idea counter displays the correct number of ideas.

### Expected Result:
The idea counter correctly reflects the total number of ideas created.

### Actual Result:
The idea counter does not update correctly.

### Severity:
Medium

### Priority:
Medium

### Status:
New

/////////////////////////////////////////////////////////////////////////////////////////

### Bug ID: 
BUG-9

### Test Case ID:
UC6-3

### Title:
Search function on My Ideas page does not work correctly

### Environment:
- Browser: Google Chrome 120
- OS: Windows 10
- Version: Demo / Test

### Preconditions:
- User is logged in

### Steps to Reproduce:
1. Click on the "My Ideas" button.
2. Type a valid keyword in the Search field.
3. Click on the "Search" button.

### Expected Result:
The idea(s) containing the searched keyword are displayed.

### Actual Result:
User is unexpectedly logged out / the system crashes.

### Severity:
Medium / High

### Priority:
High

### Status:
New
