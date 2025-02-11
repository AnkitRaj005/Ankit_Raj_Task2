# Ankit_Raj_Task2
Contact Form with Validation

This project is a simple contact form with JavaScript-based client-side validation. The form ensures that users provide valid inputs before submission.

Features
 Validates required fields such as Full Name, Email, Phone Number, Date, Gender, City, State, Country, Address, and Message.
 Email validation ensures a proper format (e.g., example@domain.com).
 Phone number validation enforces a 10-digit numeric format.
 Checks if a file is uploaded before form submission.
 Ensures that the user accepts the terms and conditions.
 Displays error messages dynamically next to the respective input fields.
 Prevents form submission if there are validation errors.
 Simulates form submission with a delay and resets the form afterward.

Technologies Used
HTML
CSS
JavaScript

How It Works

Event Listener on Form Submission
The script listens for the form's submit event.
The event.preventDefault() method prevents form submission if validation fails.

Validation Process

Each required input field is checked for completeness.
The email input is validated using a regular expression.
The phone number input is validated to ensure it contains exactly 10 digits.
If errors are found, they are displayed below the respective input fields.
Simulated Submission

If all fields are valid, the form simulates submission by displaying a "Submitting..." message.
A setTimeout function simulates a delay of 2 seconds before showing a success message.
The form is then reset, and the submit button is re-enabled.
