
Foody Web App
Project Description

Foody Web App is a web application designed for sharing culinary experiences and recipes. 
Users can add foods, create and manage their own food cards.

Application URL

http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws.com:85/

The project supports functionalities for both registered and unregistered users.

Key Features
For Unregistered Users:

View Home Page with main information and call-to-action.

Access to SIGN UP and LOG IN buttons.

Navigation to About Us page via the LEARN MORE button.

Limited access to content and information.

For Registered Users:

Access to a personalized Home Page.

Add new foods via Add Food feature.

Manage created Food Cards (VIEW, EDIT, DELETE).

Search for foods using the Search field.

Manage My Profile (edit personal data and view added foods).

Test Cases Structure

All test cases are organized by functionality and stored in the /tests folder:

Home Page

Verify navigation, sections, and buttons.

User Registration

Validate registration form fields and input data.

User Sign In

Validate login functionality, Forgot Password, and Create New options.

Profile Management

Verify My Profile and Edit functionalities.

Add Food

Validate adding foods and form correctness.

Food Cards Management

Verify VIEW, EDIT, and DELETE buttons on food cards.

Documented Bugs

All identified bugs are documented in the /bugs folder. Examples:

BUG-1: LEARN MORE button does not redirect to About Us Page.

BUG-2: Join US picture does not lead to SIGN UP page.

BUG-3: Missing hyperlink to Terms and Conditions.

BUG-4: Forgot Password link does not work.

BUG-5: VIEW button on Food Card is missing.

BUG-6: EDIT button on Food Card is not working.
