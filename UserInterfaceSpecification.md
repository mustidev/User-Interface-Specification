#  User Management Screen UI Specification

## Introduction
This document outlines the requirements and specifications for the User Management Screen UI. The screen will be used by administrators to manage users within the system.

## Requirements
- The screen should display a list of all users in the system with their names, email addresses, and roles.
- The list should be orderable by username, email address, id, enabled value(true or false).
- Users are automatically assigned id values according to the order in which users are added to the list.
- Administrators which are admin and super admin, should be able to add new users to the list and order users from the list.
- When adding a user, the administrator should be able to specify the user's username, display name, email address, phone, role and enabled value.
- The role options should include "Guest, "Admin" and "SuperAdmin".
- The "enabled" field can be ticked or not.If it is ticked enabled value becomes true and if not then enabled values is false.
- The screen should have a clear and intuitive layout, making it easy for administrators to manage users.


## UI Components
- User List: A table that displays all users in the system, including their usernames, email addresses, id's and enabled values.
- Sort icon : An icon in the list values that orders users in the list depending on the values that will be ordered
- Hide Disabled User Checkbox: A checkbox for hiding the user whose enabled value is false.
- New User Button: A button that shows a modal for adding a new user to the system.
- Save User Button: A button that saves the user and user's informations to the list.
- New User Modal: A modal that appears when the New User button is clicked. It includes fields for entering the user's username, display name, phone, email address, user roles and enabled checkbox.
- Enabled Checkbox: A checkbox which is shown when a new user be saved and it assigns the enabled value as true if it is checked.
 
## Behavior
- When the User Management Screen is first loaded, the user list should be displayed with all users in the system.
- When the Sort icon is used, the list should be ordered based on the clicked term.
- When the New User Button is clicked, the New User modal should appear, allowing the administrator to enter the user's information.
- When the Save User Button is clicked, the user's information should be submitted to the system.
- When the Hide Disabled User Checkbox is ticked, users should be hiden whose enabled values are false.
- 
## Conclusion
The User Management Screen should provide administrators with an intuitive and efficient way to manage users within the system. By following the specifications outlined in this document, the screen will meet the requirements and provide a positive user experience.
