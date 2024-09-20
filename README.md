# tasktwelve
Registration Form with validation

This project demonstrates a simple registration form using HTML, CSS, and JavaScript. The form includes fields for First Name, Last Name, Email, Phone Number, Password, and Password Confirmation. The project includes client-side validation to ensure both password fields match before form submission.

Features
A registration form with fields for user input.
JavaScript validation that checks if the "Password" and "Confirm Password" fields match.
Styling with an external CSS file to make the form visually appealing.
On successful submission, the form redirects to a submit.html page with a registration success message.
The project is set up to work with Live Server in VSCodium.
Files
index.html:

The main file containing the registration form.
Links to external CSS and JavaScript files for styling and validation.
submit.html:

The success page displayed after form submission.
Contains a simple message indicating the registration was successful.
style.css:

The external CSS file that styles the form and buttons to improve the user experience.
script.js:

The external JavaScript file that handles password validation, ensuring both password fields match before form submission.
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/namitha3041/tasktwelve.git
Open the folder in VSCodium.

Run Live Server:

Right-click on index.html in the file explorer and select "Open with Live Server".
This will open the registration form in your default web browser.
Submit the Form:

Fill out the form and ensure the passwords match.
Click Submit to be redirected to the success page (submit.html).
Validation
The JavaScript file (script.js) checks if both passwords are the same when the form is submitted.
If the passwords do not match, an alert will appear, and the form will not be submitted.
Moving CSS to style.css
Initially, all the CSS code was placed in the index.html file for simplicity.
The CSS was later moved to a separate style.css file to improve maintainability and organization.
This allows you to keep HTML and CSS separate for easier modification in larger projects.
Moving JavaScript to script.js
The JavaScript used for password validation was initially embedded in the index.html file.
The script was moved to an external file (script.js) to follow best practices by separating structure (HTML), style (CSS), and behavior (JavaScript).
Future Improvements
Add server-side validation and processing to make the form fully functional in a real-world application.
Implement further input validation, such as email format checks and phone number restrictions.
