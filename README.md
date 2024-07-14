#Personal Finance Tracker using Python
This project is a personal finance tracker built using Python and SQLite. It allows users to track their expenses, view recorded expenses, calculate daily, monthly, and yearly expense totals, and exit the program.

#Features
Add a new expense with a date, category, description, and amount
View all expenses recorded
Calculate daily, monthly, and yearly expense totals
Allow the user to exit the program

#Implementation
The project is implemented in two phases:

#Phase 1: Storing Data in a CSV File
In the initial implementation, data is stored in a CSV file. The program collects expense details from the user and appends this data to the CSV file. The program can read the CSV file and display all recorded expenses, calculate totals, and provide an option for the user to exit the program.

#Phase 2: Transitioning to SQLite Database
In the second phase, the project transitions to using an SQLite database for improved data management. The program creates an SQLite database named expense_tracker.db and a table called expenses to store expense data. This provides better data management, including faster queries and greater flexibility.

#GUI
The project includes a GUI built using the tkinter library, which provides a user-friendly interface for recording and tracking expenses. The GUI script uses the expense_tracker.py module to handle expense-related operations.

#Dependencies
tkinter library (for the GUI)
expense_tracker.py module (to handle expense-related operations)

#Usage
Setup: Ensure that you have the expense_tracker.py module in the same directory or in a location accessible to your Python environment.
Running the GUI: Execute the GUI script by running the Python file (e.g., expense_tracker_gui.py) in your terminal or IDE.
GUI Interface:
Date Entry: Enter the date of the expense in the provided field.
Category Entry: Specify the category of the expense. *... (other GUI interface details)
This project provides a simple yet effective way to track personal expenses using Python and SQLite.
