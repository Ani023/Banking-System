# Banking-System
This is a C++ project on a banking system that provides a console-based user interface for a simple banking application. The project is implemented using object-oriented programming (OOP) concepts and features classes, objects, and various standard C++ libraries.

The project is designed with three classes: Account, Bank, and InsufficientFunds. The Account class defines the attributes and methods related to an individual account, including the account number, first and last name of the account holder, and the current balance. The Bank class contains a collection of Account objects and manages their creation, deletion, and other operations. The InsufficientFunds class is an exception class that is thrown when a withdrawal request exceeds the current balance.

The Bank class also uses standard C++ libraries like fstream, vector, and map. The fstream library is used for reading and writing account data to and from a file, while the vector and map libraries are used to store and manage collections of Account objects.

The main function implements a console-based user interface that allows users to perform various banking operations like opening a new account, checking the account balance, depositing and withdrawing funds, closing an account, and displaying all the available accounts. The program reads user input from the console and provides output accordingly.

The code is well-commented, and the variables, functions, and classes are named descriptively to enhance the code's readability and maintainability. The project is organized into logical sections and follows standard C++ programming conventions
