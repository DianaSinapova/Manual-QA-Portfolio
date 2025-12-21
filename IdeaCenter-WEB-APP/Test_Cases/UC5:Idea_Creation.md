### Test Case ID:
UC5-1

### Title:
Verify that the Create New Idea page contains all required fields and buttons

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "Create New Idea" button.
2. Observe the Create New Idea page and verify that all required fields and buttons are present.

### Expected Result:
The Create New Idea page includes:
- Title field
- Add Picture field
- "Describe your idea" text area
- CREATE button

### Actual Result:
All required fields and buttons are displayed as expected.

### Status:
Pass

### Bug ID:
N/A



////////////////////////////////////////////////////////////////////////////////////////////


### Test Case ID:
UC5-2

### Title:
Verify that a user can create a new idea and it is visible on the My Ideas page

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "Create New Idea" button.
2. Fill in all required fields.
3. Click on the "CREATE" button.

### Expected Result:
User is redirected to the My Ideas page, and the newly created idea is visible.

### Actual Result:
User is redirected to the My Ideas page, and the newly created idea is visible.

### Status:
Pass

### Bug ID:
N/A



//////////////////////////////////////////////////////////////////////////////////////////////


### Test Case ID:
UC5-3

### Title:
Verify that creating a new idea with an empty Title field is not possible

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "Create New Idea" button.
2. Fill in all required fields except the Title field.
3. Click on the "CREATE" button.

### Expected Result:
An error message is displayed indicating that the Title field is required.

### Actual Result:
An error message is displayed indicating that the Title field is required.

### Status:
Pass

### Bug ID:
N/A


////////////////////////////////////////////////////////////////////////////////////////////////



### Test Case ID:
UC5-4

### Title:
Verify that creating a new idea with an empty "Describe your idea" field is not possible

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "Create New Idea" button.
2. Fill in all required fields except the "Describe your idea" field.
3. Click on the "CREATE" button.

### Expected Result:
An error message is displayed indicating that the "Describe your idea" field is required.

### Actual Result:
An error message is displayed indicating that the "Describe your idea" field is required.

### Status:
Pass

### Bug ID:
N/A



///////////////////////////////////////////////////////////////////////////////////////////


### Test Case ID:
UC5-5

### Title:
Verify that the idea counter on the My Profile page updates correctly after creating a new idea

### Preconditions:
- User is logged in

### Test Steps:
1. Click on the "Create New Idea" button.
2. Fill in all required fields to create a new idea.
3. Click on the "CREATE" button.
4. Click on the "My Profile" button.
5. Observe whether the idea counter displays the correct number of ideas.

### Expected Result:
The idea counter correctly reflects the total number of ideas created.

### Actual Result:
The idea counter does not update correctly.

### Status:
Fail

### Bug ID:
BUG-8


