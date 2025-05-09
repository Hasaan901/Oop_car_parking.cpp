📚 Library Management System (C++)
Description
This is a simple console-based Library Management System written in C++. It allows users to register, log in, view available books, search for a specific book, borrow books, and return them. It includes a fine system for late returns.

Features
User Registration (dummy, not stored)

User Login (only works with hardcoded credentials: Hasaan, 123)

Display all available books

Search for books by title, author, or ISBN

Borrow books (decreases stock)

Return books (increases stock)

Includes a fine of Rs. 500 for late returns

How It Works
1. Startup
The program displays a logo.

Users are prompted to register or log in.

2. Authentication
Registration: Asks for a name and password (not stored or used).

Login:

Username: Hasaan

Password: 123

Only these credentials allow access to the main menu.

3. Main Menu (after login)
Options include:

View all books: Displays book details (title, author, ISBN, stock).

Search for books: Search by title, author, or ISBN.

Borrow books: Reduces the book stock by 1.

Return books: Increases stock. A fine is applied if returned after day 12.

Exit: Terminates the program.
