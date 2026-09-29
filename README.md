# Simple-banking-transaction-system-
Simple Banking Transaction System is a basic Python project designed to perform common banking operations through a menu-driven program. The project allows a user to create an account, check balance, deposit money, withdraw money, and view basic account details.
Simple Banking System
A simple console-based banking system built with Python. This project allows users to check their balance, deposit money, withdraw money, and exit the banking system through an interactive menu.
Features
  Check current account balance
  Deposit money
  Withdraw money
  Prevent withdrawal when the balance is insufficient
  Validate positive deposit and withdrawal amounts
  Interactive menu-based interface
  Exit the banking system safely
Technologies Used
Python 3
Standard Python functions
input() for user interaction
Global variable for maintaining account balance
Starting Balance
The account starts with a balance of:
₹5000

How It Works
When the program starts, it displays a menu with four options:
----------- MENU -----------
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
----------------------------

1. Check Balance
Displays the user's current account balance.

3. Deposit Money
4. 
Allows the user to enter an amount to deposit.
If the amount is greater than zero, it is added to the current balance.

5. Withdraw Money
   
Allows the user to withdraw money from the account.
The program checks:

The amount must be greater than zero.
The withdrawal amount must not exceed the available balance.
If the balance is insufficient, the withdrawal is rejected.

4. Exit

Closes the banking system and displays a thank-you message.
Example
====================================
       SIMPLE BANKING SYSTEM
====================================

----------- MENU -----------
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
----------------------------

Enter your choice: 1

Your current balance is: ₹ 5000

Example deposit:
Enter your choice: 2

Enter the amount you want to deposit: ₹1000
₹ 1000.0 has been deposited successfully.
Updated balance: ₹ 6000.0

Example withdrawal:
Enter your choice: 3

Enter the amount you want to withdraw: ₹500
₹ 500.0 has been withdrawn successfully.
Remaining balance: ₹ 5500.0

Project Structure
simple-banking-system/
│
├── banking_system.py
└── README.md

How to Run
1. Install Python
Make sure Python 3 is installed on your computer.
Check your Python version:

python --version

or:
python3 --version

2. Download or Clone the Project
Clone the repository:
git clone <your-repository-url>

Move into the project directory:
cd simple-banking-system

3. Run the Program
python banking_system.py

On some systems, use:
python3 banking_system.py

Concepts Demonstrated
This project is useful for beginners learning Python because it demonstrates:
Variables
Functions
global variables
Conditional statements (if, elif, else)
while loops
User input
Arithmetic operations
String formatting/output
Basic input validation
Limitations
This is an educational project and not a real banking application.
Account information is not stored permanently.
The balance resets to ₹5000 whenever the program is restarted.
There is no login or authentication system.
There is no database.
It currently does not handle non-numeric input gracefully.
It is designed for a single account.
Future Improvements
Possible improvements include:
Add username and password authentication
Store account information in a database
Add transaction history
Add multiple bank accounts
Add fund transfer functionality
Handle invalid/non-numeric input using try/except
Use Decimal instead of float for monetary calculations
Add an account creation feature
Add PIN verification

A beginner-friendly Python project created to demonstrate the fundamentals of functions, loops, conditions, and user input.
License
This project is intended for educational purposes. You are free to modify and improve the code for learning and personal projects.
