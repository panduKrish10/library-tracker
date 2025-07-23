# 📚 Library Management System (C++)

## 🔍 Overview

This is a console-based **Library Management System** written in **C++**. It allows the user to:

- Add new books with a name and author.
- Borrow books (updates the borrow status).
- Return books (marks the book as available again).
- Display all books in the library.
- Display only the borrowed books.

This program is entirely written in **C++** and runs on any system with a C++ compiler.

---

## 💻 How to Compile and Run

### 🛠️ Compile using g++
```bash
g++ -o library library.cpp
```

### ▶️ Run the program
```bash
./library
```

---

## 🧾 Features

- ✅ Add books by entering title and author.
- 📖 View a list of all books with their current status (Available or Borrowed).
- 📕 View only borrowed books.
- 🔄 Borrow or return a book by selecting its index.
- 🚫 Input validation for incorrect indexes and status.
- 📋 Simple and user-friendly menu interface.

---

## 🧪 Sample Interaction

```
*** Library Menu ***
1. Add Book
2. Return Book
3. Borrow Book
4. Display All Books
5. Display Borrowed Books
6. Exit
Enter your choice: 1
Enter book name: The Great Gatsby
Enter author name: F. Scott Fitzgerald
Book added successfully!

Enter your choice: 4
1. Book: "The Great Gatsby" by F. Scott Fitzgerald [Available]

Enter your choice: 3
Enter index of book to borrow: 1
Book borrowed successfully!

Enter your choice: 5
1. Book: "The Great Gatsby" by F. Scott Fitzgerald

Enter your choice: 2
Enter index of book to return: 1
Book returned successfully!
```

---

## 🧱 Code Structure

- `Book` class: Stores book name, author, and borrow status.
- `Library` class:
  - Stores a list of books.
  - Has methods to add, borrow, return, and display books.

---

## 📌 Requirements

- Any C++11 or newer compiler.
- No external libraries required.
- Works on Windows, Linux, or macOS terminals.

---

## 📚 Project Information

- **Project Title:** Library Management System
- **Language Used:** C++
- **Type:** Console Application
- **Topic Covered:** Classes, Objects, Vectors, Input/Output, Conditionals

---

## 👨‍💻 Author

- **Name:** *[Your Name Here]*
- **Institution:** *[Your College/University]*
- **Submitted for:** *[Course or Subject Name]*

---

## 📜 License

This project is free to use for learning and academic purposes.
