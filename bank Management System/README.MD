Bank Management System – Project Statement =

Project Statement

The Bank Management System is a console-based application developed using Core Java. It is designed to perform basic banking operations such as creating a bank account, depositing money, withdrawing money, and displaying account details. The project is built using Object-Oriented Programming (OOP) concepts, making it a practical example for beginners to understand how Java is used in real-world applications.
Each customer is represented as an object of the BankAccount class. Every object stores its own account information, including the account holder's name, account number, and account balance. The application automatically generates a unique account number for each new account using a static variable, while customer-specific details such as name and balance are stored in instance variables.

The system provides a menu-driven interface, allowing users to interact with the application by selecting different banking operations. It also performs basic validations, such as checking whether sufficient balance is available before allowing a withdrawal.

Example = 

Suppose a bank has three customers:

Account No.	Account Holder	Balance
1001	Ansh	₹50,000
1002	Swayam	₹75,000
1003	Ved	₹90,000

When the program starts, the user can choose an operation:

====== BANK MANAGEMENT SYSTEM ======

1. Create Account
2. Deposit Money
3. Withdraw Money
4. Display All Accounts
5. Exit

Enter Choice: 2
Example 1: Deposit Money
Enter Account Number: 1001
Enter Deposit Amount: 5000

Deposit Successful!
Current Balance: ₹55000
Example 2: Withdraw Money
Enter Account Number: 1002
Enter Withdraw Amount: 10000

Withdrawal Successful!
Current Balance: ₹65000
Example 3: Display All Accounts
--------------------------------
Account Number : 1001
Name           : Ansh
Balance        : ₹55000
--------------------------------

--------------------------------
Account Number : 1002
Name           : Swayam
Balance        : ₹65000
--------------------------------

--------------------------------
Account Number : 1003
Name           : Ved
Balance        : ₹90000
--------------------------------
Concepts Used in This Project
Class: BankAccount, BankSystem
Object: Each customer's bank account (acc1, acc2, acc3)
Instance Variables: accountHolder, balance, accountNumber
Static Variable: nextAccountNumber
Constructor: Initializes account details
Methods: deposit(), withdraw(), display()
Array of Objects: Stores multiple bank accounts
Loops: Display menu repeatedly
Switch Case: Handles user menu selection
Conditional Statements: Checks sufficient balance before withdrawal
Conclusion

This project helps beginners understand how Java and Object-Oriented Programming concepts are applied in a real-world banking system. It improves programming logic, strengthens OOP fundamentals, and provides a foundation for developing more advanced Java applications such as ATM systems, online banking software, or database-connected banking systems.
