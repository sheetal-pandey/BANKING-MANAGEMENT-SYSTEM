This project demonstrates a complete Banking System built using Python's Object-Oriented Programming (OOP) concepts. The system allows users to create accounts, deposit money, withdraw funds, check balances, and view all stored accounts. It showcases practical implementation of OOP to model a real-world financial application.
This project is building a digital infrastructure for a bank. This needs to create a system that handles different types of accounts (Savings and Current) and a central Bank class to manage them. The system operates using the Indian Rupee (₹).
1. Classes & Objects: Represents accounts and banking operations.
 2. Inheritance: SavingsAccount and CurrentAccount that are child class inherits from parent class Account.
 3. Polymorphism: withdraw () method is overridden differently in each subclass.
 4. Encapsulation: Account details remain inside objects.
 5. Abstraction: User interacts through simple menu options while internal logic is hidden
 The system follows the following structure:
 • Account Class: It is a Base class which contains common attributes and methods.
 • SavingsAccount Class:  This class inherits properties from parent class Account and maintains minimum balance.
 • CurrentAccount Class: This class inherits properties from parent class Account and supports overdraft facility.
 • Bank Class: This class Stores and manages all accounts using a dictionary.
 • User Interaction: It is done through a text based menu system.
