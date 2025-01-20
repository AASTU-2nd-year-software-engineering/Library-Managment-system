# Hello, this is Library Managnment system project

# About us
+ second year software engineering student
# Memeber
+  **Daniel Gashaw**  (ETS0387/16)(**Maxd646**)
+  **Dawit Lulie**   (ETS0400/16)(**DawitLulie**)
+  **Emran Seid**    (ETS0472/16)(**Emran-Mohammed**)
+  **Feven Tassew**  (ETS0557/16)(**feven1805**)
+  **Hiwot Anmut**   (ETS0549/16)(**chayim97**)
+  **Fenet Firomsa** (ETS0721/16)(**fenetfiromsa**)
+  #Library Management System
+  ##Introduction
Managing a library can be a challenging task, especially when it comes to tracking book inventories, member information, and borrowing records. The Library Management System is a C++ program designed to simplify these operations by providing an easy-to-use interface for librarians or administrators.

This system is perfect for managing libraries in educational institutions, small organizations, or any setting that requires a streamlined way to handle books and members.

##What This Program Does
The Library Management System provides the following functionalities:

**1. Manage Books:**

+ Display a list of all available books.
+ Add new books to the library.
+ Update the number of copies of existing books.
+ Remove books from the library.
+ Search for books by their unique ID.

**2. Manage Members:**

+ Add members to the library system.
+ Display the list of registered members.

**3. Borrow Books:**

+ Members can borrow books from the library.
+ The program keeps track of borrowed books and updates the available copies.
  
**4. Data Persistence:**

+ Save the library's current data to a file.
+ Load previously saved library data.
##Key Features
+ **Book Management:**

  + Add, display, update, remove, and search for books.
  + Keep track of the number of copies for each book.
    
+**Member Management:**

  + Register new members.
  + Maintain a list of all members.
    
+**Borrowing System:**

  + Allow members to borrow books.
  + Automatically reduce the number of available copies when a book is borrowed.
    
+**Data Storage:**

  + Save the library's book collection to a file for later use

  #  Getting Started
##Prerequisites
To run this program, you will need:

+ A computer with a C++ compiler installed (e.g., GCC, MinGW, or Visual Studio).
+ The source code files from this repository.
## Installation and Setup
Download the Code:

+ Clone this repository or download the ZIP file.
+ Extract the contents to a directory of your choice.
##Compile the Program:

Use a C++ compiler to compile the source code file.
Example command (GCC): 'g++ -o LibraryManagementSystem LibraryManagementSystem.cpp'

##Run the Program:
Execute the compiled file: './LibraryManagementSystem'

## How to Use
**Main Menu:**

Upon starting the program, you’ll see a menu with options to manage books, members, and more.

**Book Operations:**

+ Add new books by providing the book ID, title, author, and number of copies.
+ Display all books in a tabular format.
+ Update the number of copies for an existing book.
+ Remove a book using its ID.
+ Search for a specific book by its ID.

**Member Operations:**

+ Register new members by providing their ID and name.
+ Display the list of all members.

**Borrowing Books:**

+ Enter the member's ID and the book's ID to borrow a book.
+ The system will check for the book’s availability and update the records accordingly.
  
**Save and Load Data:**
+ Save the library’s current state to a file (library_data.txt).
+ Load previously saved data to continue from where you left off.

