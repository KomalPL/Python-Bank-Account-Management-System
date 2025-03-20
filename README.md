# Python-Bank-Account-Management-System
A Python-based Bank Account Management System that allows users to create accounts, perform deposits, withdrawals, and transfers, and view transaction history and passbooks. Account data is saved persistently using pickle, ensuring data retention. Designed to help learners practice Python, file handling, and object-oriented programming.
Bank Account Management System
This is a simple command-line Python-based Bank Account Management System. It allows users to manage their bank accounts by providing features like creating new accounts, viewing account details, making deposits/withdrawals, transferring funds between accounts, viewing transaction history, and generating passbooks.

Features
Open a New Account: Create a new account with an initial deposit.
View Account Details: View account holder details and balance.
Perform Transactions: Deposit money, withdraw money, and transfer funds between accounts.
View Transaction History: View the list of transactions made on an account.
View Passbook: View the passbook (transactions and account balance).
Persistent Data Storage: Account details and transactions are saved and loaded from files using pickle.
Prerequisites
Ensure you have Python 3.x installed on your machine. If not, you can download and install it from here.

No external libraries are required for this project, as it uses standard Python libraries only.

Files
bank_accounts.pkl: Stores the account information.
transactions.pkl: Stores the transaction history.
These files are automatically created when you run the program.

How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/bank-account-management-system.git
Navigate to the project directory:

bash
Copy
Edit
cd bank-account-management-system
Run the script:

bash
Copy
Edit
python bank_account_management.py
Follow the interactive menu to perform actions on your bank account.

Usage
Once the script is running, you will be presented with a menu where you can select one of the following options:

Open a new account: Create a new bank account with the provided details.
View account details: View information like account holder name, account number, account type, and balance.
Perform transactions: Deposit money into an account, withdraw money, or transfer money between two accounts.
View transaction history: View all the transactions made on the account.
View passbook: View the detailed passbook containing the transaction history and current balance.
Exit: Exits the program and saves the account data to the file.
Example:
bash
Copy
Edit
Bank Account Management System
1. Open a new account
2. View account details
3. Perform transactions
4. View transaction history
5. View passbook
6. Exit
Enter your choice: 1
Enter account holder's name: John Doe
Enter account type (Savings/Current): Savings
Enter initial deposit amount: 10000
Account created successfully! Account Number: 1234567890
Data Persistence
The program stores the following data in local files:

Bank Account Information: Saved as bank_accounts.pkl.
Transactions: Saved as transactions.pkl.
Both files are used to persist account and transaction data, so it remains even after you close the program.

Contributing
If you would like to contribute to this project, feel free to fork the repository, make your changes, and create a pull request. Here are some ways you can contribute:

Add new features
Fix bugs
Improve documentation
