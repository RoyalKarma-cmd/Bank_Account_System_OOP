Bank Account System (OOP)
Project Overview

Bank Account System is a Python project built using Object-Oriented Programming (OOP) concepts.

The project demonstrates the use of:

Classes and Objects
Constructors
Methods
Encapsulation
Private Variables
Conditional Statements

The system allows users to deposit money, withdraw money, and check account details while protecting the account balance using encapsulation.

Features
Account Creation

Stores:

Account Holder Name
Account Balance

Example:

Account Holder: Jaydeep
Balance: ₹10000
Deposit Money

Users can add money to their account.

Example:

₹2500 deposited successfully.
Withdraw Money

Users can withdraw money if sufficient balance is available.

Example:

₹500 withdrawn successfully.
Balance Check

Displays the current account balance.

Example:

Current Balance: ₹12000
Insufficient Balance Protection

Prevents users from withdrawing more money than available.

Example:

Insufficient Balance
OOP Concepts Used
Class
class BankAccount:

Blueprint for creating bank account objects.

Object
account = BankAccount("Jaydeep", 10000)

Represents an actual bank account.

Constructor
def __init__(self, account_holder, balance):

Initializes account details when an object is created.

Methods

Functions inside the class:

deposit()
withdraw()
show_balance()
show_details()
Encapsulation

Balance is stored as a private variable:

self.__balance

This prevents direct access from outside the class.

Project Structure
BankAccount
│
├── account_holder
├── __balance
│
├── deposit()
├── withdraw()
├── show_balance()
└── show_details()
Sample Output
~~~~~~~~~~ Account Details ~~~~~~~~~~


├── bank_account_system.py
├── README.md
└── screenshots/
