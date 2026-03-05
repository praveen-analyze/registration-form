# Registration Form with Real-Time Validation

This repository contains a simple registration form built with HTML, Tailwind CSS, and JavaScript.  
The form implements real-time validation to ensure that users submit valid data before the form can be submitted.

Repository: https://github.com/praveen-analyze/form-validation.git

---

## Project Description

A responsive form that accepts user input and validates data in real time using JavaScript:

- Name
- Email
- Password

The submit button remains disabled until all fields are correctly validated.  
Upon successful submission, a confirmation message appears and the form resets.

---

## Features

- Real-time validation with JavaScript
- Validation rules:
  - Name cannot be empty  
  - Email must be in a valid format  
  - Password must contain at least 6 characters
- Submit button is disabled until all validations pass
- Displays inline error messages
- Displays a success message after submission
- Styled using Tailwind CSS

---

## Technologies Used

- HTML5
- Tailwind CSS
- JavaScript (Vanilla)

---

## Validation Rules

### Name
- Must not be empty.
- Shows an error message if left blank.

### Email
- Must follow a valid email format.
- Uses a Regular Expression for format checking.

### Password
- Must be at least 6 characters long.
- Shows an error message if too short.

---

## How It Works

1. Each input field listens for `input` events.
2. A validation function checks current field values.
3. If all fields are valid:
   - Submit button becomes enabled.
4. On submit:
   - Default page reload is prevented.
   - A success message is shown.
   - The form resets.

---

## How to Use

Clone the repository:

```bash
git clone https://github.com/praveen-analyze/form-validation.git
