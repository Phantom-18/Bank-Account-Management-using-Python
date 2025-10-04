# Bank Account Management System (Python)

This is a Bank Account Management System built in Python, designed to simulate basic banking operations. It uses a JSON file as a database to store and manage user accounts securely. The system allows users to create accounts, deposit/withdraw money, update personal details, and delete accounts with proper authentication.

Features:-

1. Create Account – Register a new account with personal details (name, age, email, pin).
2. Deposit Money – Deposit money into your account (with limits).
3. Withdraw Money – Withdraw money securely with balance checks.
4. Show Account Details – View account information after authentication.
5. Update Details – Update your name, age, email, or PIN.
6. Delete Account – Permanently delete your account from the database.
7. JSON Database – Stores all account data persistently in a datas.json file.

Tech Stack:-

1. Python
2. JSON – for persistent storage
3. Pathlib – for file handling

How It Works:-

1. On startup, the program loads account data from datas.json.
2. Users interact via a simple menu-driven interface.
3. Authentication is required using Account Number & PIN.
4. All updates (deposit, withdraw, update, delete) are saved automatically.

Usage:- 

git clone https://github.com/your-username/bank-account-management.git
cd bank-account-management
python bank.py

Choose an option from the menu:-

1. Create an account
2. Deposit money
3. Withdraw money
4. Show account details
5. Update details
6. Delete account
