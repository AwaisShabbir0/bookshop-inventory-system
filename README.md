# 📚 Bookshop Inventory System

A simple console-based **Bookshop Inventory Management System** written in **C++**, designed for basic CRUD operations on books. This was my **first semester project**, where I practiced struct-based data handling, modular programming, and console interface logic.

---

## 📌 Features

- 📘 **Insert Book** – Add a new book with details like ID, name, author, publisher, and price.  
- 🔍 **Search Book** – Find a book using its unique ID.  
- 📝 **Update Book** – Modify the details of an existing book.  
- ❌ **Delete Book** – Remove a book record using its ID.  
- 📄 **Show All Books** – Display all stored book records.  
- 🔐 **Input Validation** – Basic checks for invalid input.  
- 🖥️ **User Interface** – Simple and clean console-based navigation using ASCII characters.

---

## 💡 Concepts Used

- `struct` for representing book records  
- Arrays for storing multiple book entries  
- Functions for modular design  
- Conditional logic and loops  
- Console I/O (`cin`, `cout`)
- Windows-specific `conio.h` for pause (`getch()`)

---

## 🛠️ Tech Stack

- **Language**: C++  
- **Compiler**: `g++` or any C++ compliant compiler  
- **Platform**: Windows (uses `conio.h`)

---

## 💻 How to Run

1. 🔧 Compile
    ```bash
    g++ bookshop.cpp -o bookshop
2. Execute
      ```bash
      ./bookshop

📝 Note: If using Linux or macOS, you may need to remove #include<conio.h> and replace getch() with cin.get().

📚 Data Fields
Each book contains the following:

id – Book ID (integer)

name – Book Title (string)

a_name – Author Name (string)

p_name – Publisher Name (string)

price – Book Price (float)

🧠 Learning Outcomes
Implemented structs and arrays in C++

Practiced modular programming through functions

Built a menu-driven system for user interaction

Gained experience with input validation and console formatting

Learned to write a functional and maintainable first C++ project

🎓 Project Info
Project Title: Bookshop Inventory System

Course: Programming Fundamentals

Semester: 1st

Language: C++

Status: Completed ✅
