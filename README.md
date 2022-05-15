# User Interface specification document

## _User List page_

### Abstract

A page for previewing the current users and adding new users to the database

## UX

- **Table for showing the current users**: A Table that contains 4 columns (id, username, emails, enabled), you can sort and filter all 4 columns, the table should be shown on the left side of the screen.

  - The titles row cells will contain arrows icons (up arrow and down arrow) to be used to sort the table by the cell they are in, also there is a filter icon that will be used to show filters for the table

  - if the table sorted ascending to some column, the column title should show only the up arrow, but if the table sorted descending to this column, the column title should show only the down arrow,

  - if the table is not sorted by specific column the column title should show both arrows one over the other

- **Adding New user Button**: this Button should be shown on top of the table in case the table was empty at first so the first thing you want to do is add a new user.

- **Checkbox Hide Disabled User**: This checkbox will filter out all the disabled users from the table.

- **Form for adding the new user details**: (user Name, Display Name, Phone, Email, user roles (the roles are guest, admin, or SuperAdmin, and a checkbox to create an already enabled user) this form should be next to the table at the right side from the screen.

- **Save user Button**: this Button should be shown on top of the table to be inlined with the adding button.

## UI

- **The Table**: it will have a light background with colored overall, **the titles row cells** will have a blue background and a white text and icons as well, **other rows** will have dark text with a light blue background color for the even rows and a light one for the odd rows.

- **The Buttons**: will have a blue background when they are active and the user can click them, and a lighter background when they are disabled and the user can't click them and the text will be white.

- **`+ New User Button`**, **Save User**, and the **Hide Disabled User checkbox** will be at the top of the screen in one section with a light grey background, The Hide Disabled user have black text.

- **The Adding User Form**: should contain textFields for the input and each information should be one line and the other underneath it, New roles will be a select component with three options (admin, super admin, guest)

## Functionality

- The table columns should contain the filter functionality to filter any column the user wants by clicking the filter icon on the title row

- The user should be able to sort the data in the table by any of the columns by using the sorting arrows on the title row

- At the start, the Table will be center-aligned and the **add user form** should be hidden, and by clicking on the **`+ Add User`** button the table should go to the right side of the screen and the **add user form** should appear on the right half of the screen

- Save User Button after you click it the data should be saved and shown in the table

- checking the **`Hide Disabled Users`** checkbox will filter out all the disabled users from the table
