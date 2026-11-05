# Contact Book App Advanced

A polished contact book web application built with **HTML**, **JavaScript**, **Bootstrap 5**, and **Font Awesome**. This project connects to the IT Varsity Contact Book API and allows users to securely manage contacts through a modern, responsive interface.

## Overview

This application provides a simple contact management experience where users can:
- view all contacts
- add new contacts
- edit existing contacts
- delete contacts
- upload profile images
- store an API key in the browser for authenticated access

The interface is styled with Bootstrap and enhanced with custom UI components for a cleaner user experience.

## Features

- Responsive contact list layout
- Add contact form with image upload preview
- Edit contact details in place
- Delete confirmation modal
- API key validation and local storage support
- Contact avatar display with fallback initials
- Refresh button to reload contacts from the API
- Styled notifications for success and error states

## Built With

- HTML5
- JavaScript (Vanilla JS)
- Bootstrap 5.3
- Font Awesome
- IT Varsity Contact Book API

## Project Files

- `index.html` — main contact listing page
- `add-contact.html` — page for adding a new contact
- `edit-contact.html` — page for viewing, editing, and deleting a contact
- `enter-api-key.html` — page for entering and validating an API key
- `config.js` — stores the API base path and API key check logic
- `Project Files/` — contains duplicate support files used by the app

## How the App Works

1. The app checks whether an API key is stored in `localStorage`.
2. If no API key exists, the user is redirected to `enter-api-key.html`.
3. The API key is validated against the Contact Book API.
4. Once validated, the app can fetch and manage contact records.
5. Contacts are displayed on the home page and can be opened for editing or deletion.

## API Base URL

```text
https://mysite.itvarsity.org/api/ContactBook/
```

## API Endpoints Used

- `controller/api-key/`
- `controller/get-contacts/`
- `controller/insert-contact/`
- `controller/edit-contact/`
- `controller/delete-contact/`
- `controller/uploads/`

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Ty-xn-ITvarsity/Module-10-Assessment-2.git
```

### 2. Open the project

Open the folder in your preferred code editor.

### 3. Run the application

Open `index.html` in your browser.

If no API key is saved yet, the app will automatically redirect you to `enter-api-key.html`.

### 4. Enter your API key

Provide a valid API key to gain access to the contact management features.

## Screens / Pages

### Home Page
Displays all contacts retrieved from the API.

### Add Contact Page
Allows the user to enter contact details and upload a profile photo.

### Edit Contact Page
Allows the user to update contact information or delete an existing contact.

### API Key Page
Prompts the user to enter and validate their API key before using the application.

## Notes

- A valid API key is required for the app to function.
- Contact photos are loaded from the API upload directory.
- The repository includes backup HTML files and zipped asset files.
- Some files are duplicated inside the `Project Files` folder.

## Possible Improvements

- Add contact search functionality
- Add sorting and filtering options
- Improve client-side validation
- Move inline CSS into a separate stylesheet
- Move inline JavaScript into separate script files
- Remove duplicate and backup files from the repository

## Author
Tino
Created for **Module 10 Assessment 2**.
