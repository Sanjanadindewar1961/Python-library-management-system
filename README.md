
## 📚 Library Management System 
### 🧾 Overview

The Library Management System is a simple, console-based Python program that helps manage books in a library.
It provides two modules:

* **Owner Module** – for managing books (add, update, delete, view)
* **Student Module** – for borrowing and returning books

This project is ideal for learning Python fundamentals, including data structures, functions, loops, and user input handling.

---

### ⚙️ Features

#### 👩‍💼 Owner Module

* View all books with author, year, and available copies.
* Add new books to the library.
* Update book details such as title, author, or year.
* Delete books from the library.

#### 🎓 Student Module

* View available books in the library.
* Issue a book for seven days, automatically generating issue and return dates.
* Return issued books and view any applicable fines for late returns.

---

### 🧠 How It Works

All book data is stored in memory as a list of dictionaries.
Each book contains:

* Title, author, and year of publication
* Total and available copies
* A record of issued books with student name, issue date, and return date

The system uses Python’s datetime and timedelta modules to manage and calculate return deadlines.
When a book is issued, the available copies decrease by one; when it is returned, the available count increases again.

---

### 🪜 Program Flow

When the program runs, users are presented with a main menu.
They can choose between:

1. **Owner Module** – to manage the library collection.
2. **Student Module** – to issue or return books.
3. **Exit** – to close the system.

Each module displays its own submenu for performing operations.
The system runs continuously until the user decides to exit.

---

### 🧰 Technologies Used

* Python 3
* Datetime module for handling issue and return dates
* Lists and dictionaries for data management

---

### 🚀 Future Enhancements

* Add data storage using text files or databases such as SQLite.
* Implement a student login or registration system.
* Add a search feature for finding books by title or author.
* Generate reports for issued and returned books.

