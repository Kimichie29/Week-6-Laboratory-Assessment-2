# User Registration Form

## Project Description

This project is a User Registration Form built using HTML, CSS, and JavaScript. It features real-time input validation and displays a success message upon successful form submission.

## Technologies Used

* HTML
* CSS (Tailwind CSS)
* JavaScript

## Form Validation Approach

The form uses JavaScript to validate user input in real-time. Here's how each field is validated:

* **Name:** Checks if the name is not empty and has at least 2 characters.
* **Email:** Checks if the email is not empty and matches a valid email format.
* **Password:** Checks if the password is not empty and has a minimum of 6 characters.
* **Confirm Password:** Checks if the confirm password field is not empty and matches the password field.

## State Management Strategy

The form uses JavaScript variables to manage the state of each input field and its corresponding error message. The validation functions update these variables, and the event listeners ensure that the validation is performed in real-time as the user types.

## Features

* Real-time validation of form fields.
* Clear error messages for invalid input.
* Success message display upon valid form submission.
* Responsive design using Tailwind CSS.

## How to Use

1.  Clone the repository.
2.  Open the `index.html` file in your browser.
3.  Fill out the registration form.
4.  Ensure all fields are valid to see the success message.

## Files Included

* `index.html`: The main HTML file containing the form structure.
* `styles.css`: The CSS file containing styling for the form.
* `script.js`: The JavaScript file containing the form validation logic.

## Deployment

The project can be deployed using any static site hosting service, such as:

* GitHub Pages
* Vercel
* Netlify

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to submit a pull request.
