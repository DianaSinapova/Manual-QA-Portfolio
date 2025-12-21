### Test Case ID:1

UC-1-1

### Title: 
Verify navigation bar buttons for guest users


### Preconditions: 
- User is not logged in


### Test Steps:

1. Open the application using the provided URL.
2. Observe the navigation bar.

### Expected Result:

All navigation buttons are displayed correctly:
- "SIGN IN" and "SIGN UP FOR FREE" buttons are visible on the left side.
- Link to the Home page is visible on the right side.

### Actual Result:

Buttons are not displayed according to the requirements.

### Status: 
Fail

###Bug ID: 
BUG-1


//////////////////////////////////////////////////////////////////////



### Test Case ID: 

UC-1-2

### Title: 
Validate that Carousel with three slides are with correct text 


### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the URL.
2. Observe the carousel with three slides.

### Expected Result:
The carousel should contain three slides with the following text:
- "Be part of our community"
- "Already have an account?"
- "Enjoy our site!"

### Actual Result:
The third slide contains a typo:
- "Enjoy out site!" instead of "Enjoy our site!"

### Status:
Fail

### Bug ID:
BUG-2


//////////////////////////////////////////////////////////////////////////////



### Test Case ID:
UC1-3

### Title:
Verify that the carousel changes automatically and allows manual navigation

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Observe the carousel behavior for at least 30 seconds.
3. Click the left and right arrow buttons to manually change slides.

### Expected Result:
- The carousel automatically changes slides at random intervals.
- User can manually navigate through the slides using the arrow buttons.

### Actual Result:
Works as expected.

### Status:
Pass


////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC1-4

### Title:
Verify that carousel slides contain correct call-to-action buttons

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Observe the carousel slides and their call-to-action buttons.

### Expected Result:
Two of the carousel slides contain call-to-action buttons:
- "SIGN UP FOR FREE"
- "SIGN IN"

### Actual Result:
One of the carousel slides contains a different call-to-action button:
- "Register now" instead of "SIGN UP FOR FREE"

### Status:
Fail

### Bug ID:
BUG-3


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////





### Test Case ID:
UC1-5

### Title:
Verify that all navigation buttons redirect to the correct pages

### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the provided URL.
2. Click on each navigation button and observe the page redirection.

### Expected Result:
All navigation buttons redirect to their corresponding pages:
- "Log In" → Log In page
- "Sign Up for Free" → Registration page
- Home icon → Home page

### Actual Result:
The "Log In" button on the Navbar does not work.
User is not redirected to the Log In page.

### Status:
Fail

### Bug ID:
BUG-4



////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC1-6

### Title:
Verify that all Navbar buttons are visible and correctly placed on the Home page for logged-in users

### Preconditions:
- User is logged in

### Test Steps:
1. Observe the Navbar on the Home page.

### Expected Result:
The Navbar displays the following buttons:
- Left side: Home, My Profile, My Ideas, Create Idea
- Right side: Logout button

### Actual Result:
All Navbar buttons are displayed in the correct position.

### Status:
Pass

### Bug ID:
N/A


///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC1-7

### Title:
Verify that the Home page carousel for logged-in users displays welcome slides and quick navigation buttons

### Preconditions:
- User is logged in

### Test Steps:
1. Observe the carousel on the Home page.

### Expected Result:
The carousel displays:
- Welcome slides for the logged-in user
- Quick navigation buttons:
  - "See your profile"
  - "See your ideas"

### Actual Result:
All carousel slides and buttons match the expected result.

### Status:
Pass

### Bug ID:
N/A


/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC1-8

### Title:
Verify that all navigation buttons redirect to the correct pages for logged-in users

### Preconditions:
- User is logged in

### Test Steps:
1. Click on each navigation button on the Home page.
2. Observe the page redirection.

### Expected Result:
All navigation buttons redirect to the correct pages:
- Home icon (light bulb) → Home page
- My Profile → My Profile page
- My Ideas → My Ideas page
- Create Idea → Create Idea page
- Logout → Home page (logged-out state)

### Actual Result:
All buttons redirect to the correct pages.

### Status:
Pass

### Bug ID:
N/A






### Test Case ID: 1

UC-1-3

### Title: 



### Preconditions:
- User is not logged in

### Test Steps:
1. Open the application using the URL.


### Expected Result:


### Actual Result:


### Status:
Fail

### Bug ID:

