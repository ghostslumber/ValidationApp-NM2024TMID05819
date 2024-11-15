Explanation
State Management:

The email state holds the value entered in the TextField.
The errorMessage state holds the error message to display if validation fails.
TextField:

The TextField widget is used to get the user's email input.
The isError parameter changes the border color to red if there's an error.
Validation Logic:

The isValidEmail function uses a regular expression to validate the email format.
The validateEmail function checks if the input is valid or if it needs error feedback (e.g., empty field, invalid format).
Error Feedback:

If validation fails (e.g., invalid email or empty field), an error message is displayed below the TextField.
Submit Button:

When the user clicks the "Submit" button, the app will validate the email again.
