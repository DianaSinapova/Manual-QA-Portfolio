### Test Case ID:
UC6-1

### Title:
Verify that all idea cards have the required buttons: VIEW, EDIT, and DELETE

### Preconditions:
- User is logged in and has at least one created idea

### Test Steps:
1. Click on the "My Ideas" button.
2. Observe all idea cards to check for the required buttons.

### Expected Result:
All created idea cards contain the buttons: VIEW, EDIT, and DELETE.

### Actual Result:
All created idea cards contain the buttons: VIEW, EDIT, and DELETE.

### Status:
Pass

### Bug ID:
N/A

/////////////////////////////////////////////////////////////////////////////////////////

#### Test Case ID:
UC6-2

### Title:
Verify that the VIEW and EDIT buttons on idea cards redirect to the correct pages

### Preconditions:
- User is logged in and has at least one created idea

### Test Steps:
1. Click on the "My Ideas" button.
2. Click on the "VIEW" button on an idea card.
3. Click on the "EDIT" button on an idea card.

### Expected Result:
User is redirected to the correct pages:
- "VIEW" button navigates to the idea details page.
- "EDIT" button navigates to the Edit Idea page.

### Actual Result:
User is redirected to the correct pages.

### Status:
Pass

### Bug ID:
N/A

/////////////////////////////////////////////////////////////////////////////////////


### Test Case ID:
UC6-3

### Title:
Verify that searching for an idea with correct data in the Search field works correctly

### Preconditions:
- User is logged in and has at least one created idea

### Test Steps:
1. Click on the "My Ideas" button.
2. Type a valid keyword in the Search field.
3. Click on the "Search" button.

### Expected Result:
The idea(s) containing the keyword are displayed.

### Actual Result:
The search function on the My Ideas page is not working.

### Status:
Fail

### Bug ID:
BUG-9


////////////////////////////////////////////////////////////////////////////////////


### Test Case ID:
UC6-4

### Title:
Verify that the DELETE button removes an idea from My Ideas

### Preconditions:
- User is logged in and has at least one created idea

### Test Steps:
1. Click on the "My Ideas" button.
2. Click on the "DELETE" button on an idea card.

### Expected Result:
The selected idea card is removed from the My Ideas page.

### Actual Result:
The selected idea card is removed from the My Ideas page.

### Status:
Pass

### Bug ID:
N/A





