# BAN6420-Module1-Assignment
To develop a Python program to facilitate the weekly payments of workers in Highridge Construction Company

Highridge Construction Company - Worker Payment Slips

Contents of the Folder
1. payment_slips.py   → Python script
2. payment_slips.R    → R script
3. README.txt         → This readme file

Description
This program was designed to automate the weekly generation of payment slips for 400 staff members at Highridge Construction Company.
Key features of the program include:
• Generating random profiles for 400 staff members.
• Assigning each staff member a gender and salary.
• Determining the employee level based on salary and gender using the following rules:
 - “A1” for salaries between $10,000 and $20,000.
 - “A5-F” for salaries between $7,500 and $30,000 when the staff member is female.

The output shows
-workers with valid employee levels ("A1" and "A5-F").
-workers that are not assigned to a level
This program handles errors during execution gracefully using exception handling.


How to Run the Code
--- Python Version ---
Requirements: Python
Steps:
1. Open a terminal or command prompt.
2. Navigate to the folder with the script.
3. Run the script: python payment_slips.py

--- R Version ---
Requirements: R (or RStudio)
Steps:
1. Open R or RStudio.
2. Open the script file `payment_slips.R`.
3. Run the script.

 Error Handling
Both the Python and R scripts use exception handling:
•Python: try/except
•R: tryCatch()
If any employee record contains missing or invalid data, the script logs the error and proceeds with processing the remaining employees.


