Project: Student Registration Form
This project is a Student Registration Form built using HTML, CSS, and JavaScript with Firebase as the backend to store user data.

Features:
Responsive Form Layout: HTML form elements styled with CSS to provide a visually appealing and user-friendly interface.
Form Validation: JavaScript checks that all required fields are filled, validates the email format, and ensures the contact number is 10 digits.
Firebase Integration: Uses Firebase Realtime Database to save form data (first name, last name, parent's names, date of birth, email, contact number, gender, and selected program).
User Feedback: Alerts the user upon successful submission and resets the form for a new entry.

Project Structure:
HTML (index.html): Contains the form fields and Firebase configuration script.
CSS (style.css): Styles the form layout and enhances user experience.
JavaScript (index.js):
Handles form validation on submission.
Prevents default form submission and performs checks.
Submits data to Firebase if validation is successful.
Firebase Configuration:
The Firebase configuration in the script includes apiKey, authDomain, and databaseURL. This allows real-time storage of user registration data in Firebase's Realtime Database.

How to Run:
Open index.html in a browser to view and interact with the form.
Ensure Firebase credentials in the script are active and connected to an authorized Firebase project.
