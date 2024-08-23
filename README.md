OVERVIEW
The Digital Wallet Management System is a software platform designed to manage financial transactions digitally. It allows users to transfer and receive funds, and view their account balances efficiently. This system ensures secure, fast, and convenient financial transactions, enhancing financial management for users.

Features
Manage Users: Store and manage user balances.
Process Transactions: Transfer funds between users and handle various transactions.
Transaction Confirmation: Confirm each transaction as either "Success" or "Failure".
Balance Sorting: Display users sorted by their remaining balance in descending order.
Requirements
Python Version: The code is compatible with Python 3.x.
Libraries: No external libraries are required.
Input Format
Number of Users (N):

The first line contains an integer N, the number of users.
User Data:

The next N lines each contain two integers: userID and balance, where userID is the user's identifier, and balance is the user's current balance.
Number of Transactions (T):

The line after the user data contains an integer T, the number of transactions.
Transaction Data:

The next T lines each contain three integers: from_userID, to_userID, and amount, where from_userID and to_userID are the identifiers of the users involved in the transaction, and amount is the amount transferred.
Output Format
Transaction Results:

For each transaction, print "Success" if the transaction was completed successfully or "Failure" if the transaction failed.
Sorted User Balances:

After completing all transactions, print all users sorted by their leftover balance in descending order.
