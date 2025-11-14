Bank Management System (Java)

A lightweight ATM-style banking application built using Java Swing and JDBC. This system allows users to create accounts, log in, and perform banking operations.
 Features
User Signup (3-step form)
Secure Login using Card Number & PIN
Deposit & Withdrawal
Fast Cash (Preset withdrawal options)
Balance Enquiry
Mini Statement (Recent transactions)
PIN Change

Tech Stack

Java - Swing GUI
JDBC -MySQL Database
Toedter  JDateChooser  -Date picker

Project Modules (Short Summary)

 Login
Authenticates using card number + PIN from the login table.
Signup (3 Pages)
Signup 1: Personal details → stored in signup
Signup 2: Additional info → stored in signuptwo
Signup 3: Account details → generates Card No & PIN, stored in signupthree and login
 Main Menu (ATM Screen)
Routes to all banking services.
Deposit
 Withdraw / Fast Cash
Balance Enquiry
Mini Statement
 PIN Change
 Database Tables (Simplified)
Signup – personal info
signup two – additional info
signup three – account info
Login – card number + PIN
Bank – all transactions

▶ How to Run :-

1. Import project into any Java IDE.
2. Create MySQL database and tables (signup, signuptwo, signupthree, login, bank).
3. Update credentials in Connn.java:
connection = DriverManager.getConnection("jdbc:mysql://localhost:3306/bankSystem","root","password");
4. Run Login.java → start the application.

Contact
EMAI: - ameerhansufn@gmail.com
NUMBER: - 8431553422
LINKEDIN: - https://www.linkedin.com/in/aminuddeen-aminuddeen-584915317

DEMO
DEMO VIDEO :- https://drive.google.com/drive/folders/1UYx8HRVv4AphM3_uzQv0Hr2zqn6oQ341
SOURCE CODE :- https://github.com/aminuddeen22/Bank-Managment-System
