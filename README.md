# Library Management System

## Overview

The Library Management System is a Python-based console application that allows users to manage a collection of books. The system supports adding books, searching for books, borrowing and returning books, viewing statistics, searching by author, and saving/loading data from a file.

## Features

* Add new books to the library
* Display all books in the library
* Search for a book by title
* Search for books by author
* Borrow books
* Return borrowed books
* View library statistics
* Save library data to a file
* Load library data automatically when the program starts

## Technologies Used

* Python
* Object-Oriented Programming (OOP)
* File Handling

## Classes

### Book Class

Represents a book in the library.

**Attributes:**

* `title` – Title of the book
* `author` – Author of the book
* `published_year` – Year the book was published
* `available` – Availability status of the book

### Library Class

Manages all library operations.

**Methods:**

* `add_book()` – Adds a book to the library
* `display_books()` – Displays all books
* `search_book()` – Searches for a book by title
* `search_author()` – Searches books by author
* `borrow_book()` – Borrows a book
* `return_book()` – Returns a borrowed book
* `show_stats()` – Displays library statistics
* `save_books()` – Saves books to a file
* `load_books()` – Loads books from a file
* `create_book()` – Creates a new book using user input

## File Storage

Book data is stored in a file named:

```text
books.txt
```

Each book is saved in the following format:

```text
Title|Author|PublishedYear|Available
```

Example:

```text
1984|George Orwell|1949|True
```

## Menu Options

```text
1. Add Book
2. Display Book
3. Search Book
4. Borrow Book
5. Return Book
6. Save Books
7. Statistics
8. Search Author
9. Exit
```

## Sample Usage

### Borrowing a Book

```text
Enter your choice: 4
Enter book title: 1984
Book borrowed successfully
```

### Returning a Book

```text
Enter your choice: 5
Enter book title: 1984
Book returned successfully
```

### Searching by Author

```text
Enter your choice: 8
Enter author name: George Orwell

1984
Animal Farm
```

### Viewing Statistics

```text
Total Books: 48
Available Books: 45
Borrowed Books: 3
```

## Learning Concepts Demonstrated

This project demonstrates:

* Classes and Objects
* Constructors (`__init__`)
* Lists and Iteration
* Conditional Statements
* Functions and Methods
* File Handling
* Exception Handling
* Data Persistence
* Menu-Driven Programs
* Object-Oriented Programming Principles

## Future Improvements

* Delete books
* Update book information
* Search by publication year
* Sort books alphabetically
* Show only available books
* Show only borrowed books
* Use JSON storage instead of text files
* Add user authentication
* Create a graphical user interface (GUI)

## Author

Bhargav Patel

## License

This project is created for educational and learning purposes.
