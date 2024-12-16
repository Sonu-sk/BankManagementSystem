Bank-Management-System
Bank Management System Using Java and File Handling.

A console-based "Bank Management System" implemented in Java, featuring basic banking operations with data persistence using file handling. This project allows users to create and manage accounts, perform transactions, and view account details, all stored in a text file (accounts.txt).

Features
Account Creation:

Register a new user with:
Name
Account Number (supports large numbers using long type)
Age
Initial Balance
Account Operations:

Deposit Money
Withdraw Money (ensuring a minimum balance of ₹1000)
Balance Inquiry
Account Management:

Update Customer Details (Name, Age)
Delete an Account
Data Persistence:

Account details are stored in a file (accounts.txt) using file handling.
Supports reading and updating account data efficiently.
Getting Started
Prerequisites
Java Development Kit (JDK): Ensure JDK 8 or above is installed.
Text Editor/IDE: Use VS Code, IntelliJ IDEA, or any editor of your choice.
Running the Program
Clone the Repository:

git clone <repository-url>
cd BankManagementSystem
Compile the Code:

javac BankManagementSystem.java
Run the Program:

java BankManagementSystem
Follow the menu-driven interface to interact with the system.

File Structure
BankManagementSystem.java: The main Java file containing the program logic.
accounts.txt: The file where account data is stored.
Sample Workflow
Create an Account:

Enter details such as Name, Account Number, Age, and Initial Balance.
Perform Transactions:

Deposit money to an account.
Withdraw money, ensuring a minimum balance.
Manage Accounts:

Update customer details like Name and Age.
Delete an account when no longer needed.
View Account Balance:

Check the current balance of an account.
Example Account Format in accounts.txt
Each line represents an account:

Name,AccountNumber,Age,Balance John,234343223443211,30,15000.50

Future Enhancements
Add role-based access control.
Implement a GUI-based version.
Integrate with a database for better scalability.
Generate transaction history or mini-statements.
Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements or new features.

