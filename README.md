## User Management Screen UI Specification

Hi! This screen allows administrators to create, edit, and manage user accounts in the system.


### User Table

* **Description:**  The table displays a list of users.
* **Behavior:** clicking a row selects a user and populates the input fields for editing.

###   Input Fields

* **Description:**  List the input fields like Username, Display Name, Phone, Email, and User Roles.
* **Behavior:**  These fields are used to enter information for a new user or update an existing user's details.

### Buttons

* **Save User:**  this button saves the new or edited user information. 
* **Hide Disabled Users:**  this button toggles filtering the table to show only enabled or disabled users.
 * **New User (if applicable):**  this button opens a separate form to create a new user.

## Initial Load

When you log in to the admin panel and the page first loads, you will see a panel where you can create new users and view old users. When creating a new user, you can give the user the authorization you want. You can also filter and view old users.





## Test and Refine

First of all, it would be better to have the new user button with a pop-up window in terms of basic design principles.
As a result of my tests, I observed that users had difficulty finding the save user button. Also, it would be better in terms of UI and UX if the disabled and enabled user properties are in the same section.
