# User Management Screen UI Specification

This document provides the user interface specification for a screen used to manage users within a system.

## 1. Introduction

This screen is used for managing users in the system. The main functionalities are:

*   Listing and filtering users
*   Adding new users
*   Editing existing users

## 2. Requirements

*   User-friendly and intuitive interface
*   Fast and efficient data display
*   Adherence to accessibility standards
*   Responsive design (compatibility across different screen sizes)

## 3. UI Components

*   **User List:**
    *   Displayed in a table format
    *   Columns: Username, Display Name, Phone, Email, User Roles, Active/Inactive Status
    *   Sorting and filtering capabilities (by Username, Role, etc.)
*   **Search Bar:** For filtering the user list.
*   **"New User" Button:** Opens the new user creation form.
*   **User Details Panel (for editing):**
    *   Fields: Username (read-only), Display Name, Phone, Email, User Roles (dropdown list), Active/Inactive checkbox.
    *   "Save" and "Cancel" buttons.
*   **"Show Hidden/Inactive Users" Checkbox:** Toggles the display of inactive users in the list.

## 4. Page Behavior

*   **Initial Load:** All active users are listed. The "Show Hidden/Inactive Users" checkbox is unchecked.
*   **Search:** The user list is filtered in real-time based on the text entered in the search bar.
*   **Clicking "New User":** The User Details Panel opens in a blank state (new user creation mode).
*   **Clicking a User in the List:** The User Details Panel is populated with the selected user's information (edit mode).
*   **Clicking "Save":** Changes are saved, and the list is updated.
*   **Clicking "Cancel":** Changes are discarded, and the panel closes.
*   **Checking "Show Hidden/Inactive Users":** Inactive users are added to the list. They are hidden when the box is unchecked.

## 5. Visual Design (Summary)

*   Modern and clean design.
*   Consistent colors and typography.
*   User-experience-focused layout.
