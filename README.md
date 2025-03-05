Password Generator & Strength Checker
Overview
This project contains two Python scripts:
    1. password_generator.py – Generates strong passwords based on user preferences. 
    2. strength_checker.py – Evaluates the strength of a given password. 
Files Description
1. password_generator.py
    • Generates a password with user-specified length and character types (letters, digits, special characters). 
    • Prompts the user to accept or reject the generated password. 
    • Ensures password length constraints (minimum and maximum limits). 
2. strength_checker.py
    • Checks if a given password meets strength criteria. 
    • Evaluates the presence of uppercase letters, digits, and special characters. 
    • Ensures the password length is within the allowed range. 
    • Provides a report on missing security features if the password is weak. 
How to Use
Running Password Generator
python password_generator.py
Follow the prompts to generate a secure password.
Running Password Strength Checker
python strength_checker.py
Enter a password when prompted to receive a strength evaluation.
Requirements
    • Python 3.x 
    • No additional dependencies required. 
Notes
    • The password generator ensures a maximum length of 50 characters. 
    • The strength checker enforces a minimum length of 12 characters and a maximum of 42. 
    • Strong passwords should include uppercase letters, digits, and special characters. 
Author
Jeff

