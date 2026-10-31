# ATM and UPI Transaction Simulator

## 1. Project Overview

The **ATM and UPI Transaction Simulator** is a menu-driven Python application designed to simulate basic banking operations in a safe training environment.

It allows users to perform operations such as PIN verification, balance enquiry, cash withdrawal, deposits, UPI transfers, mini-statement generation and PIN changes.

The project demonstrates the practical implementation of Python programming concepts such as loops, conditional statements, functions, lists, tuples and exception handling.

## 2. Objectives

- To simulate basic ATM and UPI banking operations.
- To implement secure PIN verification with a maximum of three attempts.
- To apply transaction limits and minimum balance restrictions.
- To calculate cash denominations using a loop.
- To maintain transaction records using lists and tuples.
- To understand menu-driven programming and control flow in Python.

## 3. Features

- **PIN Verification:** Allows a maximum of three attempts before blocking access.
- **Balance Enquiry:** Displays the available account balance.
- **Cash Withdrawal:** Allows withdrawals while checking daily limits and minimum balance requirements.
- **Cash Denomination Calculator:** Calculates the minimum number of ₹500, ₹200 and ₹100 notes required.
- **Deposit:** Adds money to the account balance.
- **UPI Transfer:** Simulates UPI transactions with a per-transaction limit.
- **Fraud Alert:** Generates an alert after three consecutive successful large UPI transfers.
- **Mini-Statement:** Displays the five most recent transactions.
- **PIN Change:** Allows users to update their existing PIN.

## 4. Technologies Used

- **Programming Language:** Python 3.10+
- **Editor:** Jupyter Notebook
- **Version Control:** GitHub

## 5. Python Concepts Implemented

| Concept | Application |
|---|---|
| Variables and Data Types | Storing PIN, balance and transaction details |
| Conditional Statements | Validating user choices and transactions |
| While Loop | Maintaining the ATM menu |
| For Loop | PIN verification and cash denomination calculation |
| Break | Stopping after successful login or blocking access |
| Continue | Skipping invalid inputs |
| For-Else | Confirming unsuccessful PIN verification |
| Functions | Organising transaction operations |
| Lists | Storing transaction history |
| Tuples | Recording individual transaction details |
| List Slicing | Displaying the latest five transactions |
| Exception Handling | Handling invalid numerical inputs |
| File Handling | Saving and retrieving the updated PIN |

## 6. How to Run the Project

1. Install Python 3.10 or above.
2. Download or clone this repository.
3. Open the project file in Jupyter Notebook or a Python-compatible editor.
4. Run the Python program.
5. Enter the correct PIN to access the ATM menu.
6. Select the required banking operation.

**Default PIN:** `1234` (if no PIN has previously been saved).

## 7. ATM Menu Options

| Option | Operation |
|---|---|
| 1 | Balance Enquiry |
| 2 | Cash Withdrawal |
| 3 | Deposit |
| 4 | UPI Transfer |
| 5 | Mini-Statement |
| 6 | Change PIN |
| 7 | Exit |

## 8. Testing

The application was tested using different input scenarios, including:

- Correct and incorrect PIN entries.
- Three consecutive incorrect PIN attempts.
- Valid and invalid withdrawal amounts.
- Minimum balance and daily withdrawal limit checks.
- Valid and invalid deposits.
- UPI transfer validation and transaction limits.
- Consecutive large UPI transfers and fraud alerts.
- Cash denomination calculations.
- Mini-statement generation.
- PIN change and persistence after restarting the program.
- Invalid menu choices and non-numeric inputs.

## 9. Limitations

- This is an educational simulation and does not connect to any real bank or payment system.
- The PIN is stored locally for demonstration purposes and is not encrypted.
- Daily withdrawal tracking and transaction history reset when the program restarts.
- UPI ID validation checks only the basic input format.

## 10. Future Enhancements

- Store transaction history permanently using file handling or a database.
- Implement encrypted PIN storage.
- Add multiple user accounts.
- Develop a graphical user interface.
- Add date and time to transaction records.

## 11. Conclusion

This project demonstrates how fundamental Python programming concepts can be applied to develop a simple ATM and UPI transaction simulator. It provides practical experience in input validation, loops, functions, data structures, file handling and exception handling.

