### Test Case ID:
UC4-1

### Title:
Verify that all required features are present on the My Profile page

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "My Profile" button.
2. Observe the My Profile page and verify that all required features are present.

### Expected Result:
The My Profile page includes:
- A default empty profile picture
- An "Edit Profile" button
- An empty "About" section by default
- A counter displaying the number of user's ideas, initially set to 0
- A "Recent Ideas" section showing a "No ideas" message when no ideas are created
- A "Show all" link that navigates to the "My Ideas" page

### Actual Result:
All required features are displayed as expected.

### Status:
Pass

### Bug ID:
N/A



////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC4-2

### Title:
Verify that the Edit Profile button navigates to the correct page

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "My Profile" button.
2. Click on the "Edit Profile" button.

### Expected Result:
User is navigated to the Edit Profile page.

### Actual Result:
User is navigated to the Edit Profile page.

### Status:
Pass

### Bug ID:
N/A



//////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC4-3

### Title:
Verify that all required fields are present on the Edit Profile page

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "My Profile" button.
2. Click on the "Edit Profile" button.
3. Observe the Edit Profile page and verify that all required fields are present.

### Expected Result:
The Edit Profile page contains the following fields:
- Profile picture field (URL of an image)
- First Name field (maximum 60 characters)
- Last Name field (maximum 60 characters)
- City field (maximum 120 characters)
- "Describe yourself" text area (maximum 256 characters)

### Actual Result:
All required fields are displayed as expected.

### Status:
Pass

### Bug ID:
N/A
 


////////////////////////////////////////////////////////////////////////////////////////////





### Test Case ID:
UC4-4

### Title:
Verify that editing profile information on the Edit Profile page is possible

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "My Profile" button.
2. Click on the "Edit Profile" button.
3. Fill in all required fields with valid data.
4. Click on the "Done" button.

### Expected Result:
User is redirected to the My Profile page and the profile information is updated successfully.

### Actual Result:
User is redirected to the My Profile page and the profile information is updated successfully.

### Status:
Pass

### Bug ID:
N/A



//////////////////////////////////////////////////////////////////////////////////////////////////




### Test Case ID:
UC4-5

### Title:
Verify that the "Show all" link in the Recent Ideas section navigates to the My Ideas page

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "My Profile" button.
2. Click on the "Show all" link in the Recent Ideas section.

### Expected Result:
User is redirected to the My Ideas page.

### Actual Result:
User is redirected to the My Ideas page.

### Status:
Pass

### Bug ID:
N/A



////////////////////////////////////////////////////////////////////////////////////////





### Test Case ID:
UC4-6

### Title:
Verify that the Search field, button, and "No ideas yet!" message are displayed on the My Ideas page

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "My Profile" button.
2. Click on the "Show all" link in the Recent Ideas section.

### Expected Result:
User is redirected to the My Ideas page, where the following are displayed:
- Search field
- Search button
- "No ideas yet!" message if no ideas have been created

### Actual Result:
All expected elements are displayed correctly.

### Status:
Pass

### Bug ID:
N/A









