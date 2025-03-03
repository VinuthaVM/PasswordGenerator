# PasswordGenerator
A simple and customizable password generator application built using HTML, CSS, and JavaScript.

🚀 Features
Generate random passwords based on user preferences.<br>
Select password length using a slider (1-30 characters).<br>
Include/exclude the following character types:<br>
✅ Lowercase letters (a-z)<br>
✅ Uppercase letters (A-Z)<br>
✅ Numbers (0-9)<br>
✅ Symbols (@, #, $, etc.)<br>
Copy generated password to clipboard with one click.<br>
Responsive and user-friendly UI.<br>


🛠️ Technologies Used

HTML for structure<br>
CSS for styling<br>
JavaScript for functionality<br>

Assumptions:<br>
User Input Validation:<br>
-The user can specify the password length using a slider (1-30) or input field (8-20).<br>
-If no character set is selected, no password is generated.<br>
-Password length must be within the allowed range.<br>

Password Composition:<br>
-The generated password can include lowercase letters, uppercase letters, numbers, and symbols.<br>
-If a user selects multiple options, the password will be a mix of those characters.<br>

Clipboard Copying:<br>
-Clicking the copy icon copies the password to the clipboard.<br>
-A success indicator (icon change) notifies the user.<br>

UI/UX Considerations:<br>
-The interface should be responsive and visually appealing.<br>
-The "Generate Password" button should be disabled if no option is selected.<br>

🔧 Setup Instructions
Clone the repository:

git clone https://github.com/your-username/PasswordGenerator.git

Navigate to the project directory:
cd PasswordGenerator

Open index.html in your browser.
