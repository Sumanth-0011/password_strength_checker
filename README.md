# Password Strength Checker
Name:G Sumanth
Project Name: password strength checker
NO OF WEEKS: 6 weeks
Project Scope:Password Security UI Component
Intern ID:CITS2197

A modern, interactive password strength validation component designed for web applications. This project provides real-time security feedback to users as they type, encouraging the creation of stronger, more secure passwords.

## Features

- **Real-time Validation:** Instant visual feedback as the user types.
- **Strength Meter:** A color-coded progress bar that updates dynamically.
- **Security Feedback:** Descriptive labels (e.g., Too Short, Weak, Fair, Good, Strong) to guide the user.
- **Visibility Toggle:** Built-in "Show/Hide" functionality for better user experience.
- **Responsive Design:** A clean, centered card-based UI that works on various screen sizes.

## How It Works

The application uses a scoring system based on common password security best practices. It evaluates the input against five criteria:
1.  **Length:** At least 8 characters.
2.  **Uppercase:** Contains at least one uppercase letter (A-Z).
3.  **Lowercase:** Contains at least one lowercase letter (a-z).
4.  **Numbers:** Contains at least one numeric digit (0-9).
5.  **Special Characters:** Contains at least one non-alphanumeric character (e.g., !, @, #, $).

Based on the number of criteria met, the strength meter updates its width and color, and the corresponding label is displayed.

## Technologies Used

- **HTML5:** Structure of the web page.
- **CSS3:** Styling, animations, and responsive layout.
- **JavaScript (ES6):** Logic for validation, DOM manipulation, and event handling.

## Usage

1.  Copy the provided code into a single HTML file (e.g., `index.html`).
2.  Open the file in any modern web browser.
3.  Type into the password input field to see the strength meter update in real-time.

## Customization

You can easily customize the project by modifying the variables in the `<script>` section of the HTML file:
- **Colors:** Update the `colors` array in the JavaScript logic to match your brand theme.
- **Labels:** Modify the `labels` array to change the text feedback provided to the user.
- **Rules:** Adjust the Regex patterns inside the `input` event listener to add or remove specific character requirements.

## License

This project is open-source and available for educational purposes.
