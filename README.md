# Bank Account System (OOP)

## Project Overview

Bank Account System is a Python project built using Object-Oriented Programming (OOP) concepts.

The main objective of this project is to understand **Encapsulation** by protecting account balance using private variables and allowing users to interact with the balance through methods.

This project was developed as part of my Data Science and Machine Learning learning journey.

---

## Features

### Account Creation

Create a bank account with:

* Account Holder Name
* Initial Balance

---

### Deposit Money

Allows users to deposit money into their account.

Example:

```text
₹2500 deposited successfully.
```

---

### Withdraw Money

Allows users to withdraw money from their account.

Example:

```text
₹500 withdrawn successfully.
```

If the withdrawal amount exceeds the available balance:

```text
Insufficient Balance
```

---

### Check Current Balance

Displays the current balance available in the account.

Example:

```text
Current Balance: ₹12000
```

---

### Account Details

Displays account information including:

* Account Holder Name
* Account Balance

---

## OOP Concepts Used

### Class

```python
class BankAccount:
```

Blueprint for creating bank account objects.

---

### Object

```python
account = BankAccount("Jaydeep", 10000)
```

Represents a real bank account.

---

### Constructor

```python
def __init__(self, account_holder, balance):
```

Automatically initializes account details when an object is created.

---

### Methods

Methods used in the project:

```python
deposit()
withdraw()
show_balance()
show_details()
```

These methods define the actions a bank account can perform.

---

### Encapsulation

The account balance is stored as a private variable:

```python
self.__balance
```

This prevents direct access from outside the class and protects sensitive data.

---

## Project Structure

```text
BankAccount
│
├── account_holder
├── __balance
│
├── deposit()
├── withdraw()
├── show_balance()
└── show_details()
```

---

## Sample Output

```text
~~~~~~~~~~ Account Details ~~~~~~~~~~

Account Holder: Jaydeep
Balance: ₹10000

__________________________________

₹2500 deposited successfully.

Current Balance: ₹12500

₹500 withdrawn successfully.

Current Balance: ₹12000
```

---

## Technologies Used

* Python
* Object-Oriented Programming (OOP)

---

## Learning Outcomes

Through this project, I learned:

* Encapsulation
* Public and Private Variables
* Constructors
* Methods
* Data Protection
* Real-world OOP Design
* Balance Validation Logic

---

## Real-World Applications

The concepts used in this project are commonly found in:

* Banking Systems
* ATM Software
* Payment Applications
* Digital Wallets
* Financial Management Systems

---

## Future Improvements

* Transaction History
* Multiple Bank Accounts
* PIN Authentication
* Interest Calculation
* Account Transfer Feature
* File Handling for Data Storage
* Database Integration
* GUI Version using Tkinter

---

## Repository Structure

```text
bank-account-system-oop/
│
├── bank_account_system.py
├── README.md
└── screenshots/
```
