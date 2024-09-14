Features:

Patient registration with full name, password, and phone number
Patient login with authentication
Calculation of total bill based on days spent in hospital and daily rate
Display of patient information and billing details

Registration System
The program starts by prompting the user to register with a full name, password, and phone number.
The password must be at least 6 characters long, and the phone number must be exactly 10 digits long.
If the user enters invalid input, they are prompted to try again.
Once the user successfully registers, they are notified with a "Register successful!" message.

Login System
After registration, the user is prompted to login with their registered credentials (full name, password, and phone number).
If the user enters incorrect credentials, they are notified with an "Invalid Login. Re-enter the correct details." message.
If the user successfully logs in, they are notified with a "LOGIN SUCCESSFUL" message.
Billing System
After a successful login, the user is prompted to enter their patient name, days spent in hospital, and daily rate.
The program calculates the total bill by multiplying the days spent in hospital by the daily rate.
The program then displays the patient's information and billing details, including the patient name, days spent in hospital, daily rate, and total bill.

Key Concepts
User Input: The program uses the input() function to get user input for registration, login, and billing information.
Conditional Statements: The program uses if and else statements to validate user input and handle different scenarios (e.g., invalid password, invalid phone number, etc.).
Variables: The program uses variables to store user input and perform calculations (e.g., a for full name, b for password, c for phone number, etc.).
String Formatting: The program uses f-strings to format the output and display the patient's information and billing details.
