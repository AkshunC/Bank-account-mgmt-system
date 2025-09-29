Python Bank Account Management System
Objective
This project is a Python-based simulation of a bank account management system. It allows users to create and manage bank accounts, perform transactions, and retrieve account details. The system demonstrates the application of fundamental Python concepts such as variables, data structures, functions, file handling, and modules.

Features
1. Account Management
Create new bank accounts with the following attributes:
Account holder's name
Auto-generated account number (11 digits)
Account type (e.g., savings or current)
Initial balance
Retrieve account details, including:
Account holder's name
Account number
Account type
Current balance
2. Transactions
Deposit: Add money to an account.
Withdrawal: Withdraw money, ensuring the withdrawal does not exceed the current balance.
Transfer: Transfer funds between two accounts with proper validation.
Transactions automatically update the account balances.
3. File Handling
Persistent storage of account details and transaction history using the pickle library.
Load account data at program startup and save updates on termination.
Append new transactions to existing records without overwriting previous data.
4. Reports
View transaction history for any account, displaying:
Date
Type of transaction (deposit, withdrawal, transfer)
Amount
Target account (if applicable)
Generate summary statistics for each account, including:
Total deposits
Total withdrawals
Average transaction amounts (using NumPy functions)
5. User Interaction
An interactive menu for the following operations:
Open a new account
View account details
Perform transactions (deposit, withdraw, transfer)
View transaction history
Exit the program
Smooth navigation using conditional statements and loops.
6. Error Handling
Input validation to ensure:
Positive amounts for deposits and withdrawals.
Adequate balance before withdrawal or transfer.
Prevent invalid operations like transferring funds between non-existent accounts.
7. Bonus Features (Optional)
Login functionality for multiple users with username and password.
Advanced Python features like lambda functions for quick calculations.
Installation
Prerequisites
Python 3.8 or later
Required libraries:
NumPy
Pickle (built-in module)
Steps

Install NumPy:

pip install numpy  
Usage
The program provides an interactive menu to perform the following operations:

Open a new account
View account details
Deposit money
Withdraw money
Transfer money
View transaction history
View summary statistics
Exit
