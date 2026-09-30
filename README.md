# ATM System

A C++ console-based ATM system that provides basic banking operations through a simple menu-driven interface.

## Features

* Account number and PIN authentication
* Quick withdrawal with predefined amounts
* Normal withdrawal with custom amounts
* Deposit money
* Check account balance
* Logout functionality
* File-based data storage
* Automatic balance updates

## ATM Operations

* **Quick Withdraw** — Withdraw predefined amounts from 20 to 1000.
* **Normal Withdraw** — Enter a custom withdrawal amount.
* **Deposit** — Add money to the account balance.
* **Check Balance** — Display the current account balance.
* **Logout** — Return to the login screen.

## Concepts Practiced

* C++
* Structures (`struct`)
* Enumerations (`enum`)
* Vectors
* Functions
* File Handling
* Data Validation
* String Processing
* CRUD-style data management
* User Authentication
* Menu-driven Programs

## Data Storage

Client information is stored in a text file and loaded into C++ structures when the program runs.

The system automatically saves updated account balances back to the file after deposits and withdrawals.

## Purpose

This project was created to practice building a realistic banking application in C++ while applying file handling, authentication, data structures, functions, and transaction logic.
