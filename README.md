# Project-in-c
Library Management in C*

*Default Username and Password:* a7-a7

This C project is a straightforward Library Management System (LMS) that enables users to perform various tasks such as adding books to the library, searching for books, viewing the book list, deleting books, updating login credentials, and accessing program information. It uses a binary file ("A7 Lib.bin") for persistent data storage.

*Key Components and Functionalities:*

1. *File Handling:*
   - Utilizes file handling to store and retrieve book information and login credentials.
   - The file ("A7 Lib.bin") contains details like book ID, book name, author name, student name, and book issue date.
   - Login credentials (username and password) are stored in the file header.

2. *Data Structures:*
   - Structures are defined for handling dates, file headers, and book information.
   - The Date structure stores date information.
   - The sFileHeader structure includes username and password details.
   - The s_BooksInfo structure contains book details.

3. *Functions:*
   - Specific functions perform tasks such as printing messages, validating names, checking leap years, validating dates, adding books, searching for books, viewing books, deleting books, updating credentials, and providing program information.

4. *User Authentication:*
   - Users must log in with a username and password to access the library management system's main menu.
   - Default login credentials are set in the init() function.

5. *Menu-driven Interface:*
   - The main menu offers options like adding books, searching for books, viewing the book list, deleting books, updating credentials, and accessing program information.

6. *About Section:*
   - An "About" section provides information about the developer.

7. *Initialization:*
   - The init() function initializes the system by creating a binary file if it doesn’t exist and setting default login credentials.

8. *Error Handling:*
   - Basic error handling is performed, such as checking if a file exists before opening it.

9. *Looping and Exiting:*
   - Loops keep the user in the main menu until they choose to exit.

10. *Clearing the Console:*
    - The system("cls") function clears the console screen.

11. *Security Considerations:*
    - Requires valid username and password for authentication, enhancing security.

This console-based application serves as a basic example of a library management system implemented in the C programming language.
