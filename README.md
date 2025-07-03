# 🎓 Student Course Management System (C++)

This is a console-based C++ application that allows admins and students to manage student-course records with support for creation, viewing, updating, and deletion of entries. It uses file handling with `courses.txt` to store data and a B-Tree structure to organize course IDs for efficient insertion and traversal.

Developed during my internship at **Tequed Labs** as part of a data structures and systems-based learning project.

---

## 🚀 Features

- 👨‍💼 **Admin Login** with default credentials
- 👤 **Student Record Creation** (Name, USN, Courses)
- 🔍 **Search**, 📝 **Update**, 🗑️ **Delete** Student Records
- 📄 **File Handling** using `courses.txt`
- 🌳 **B-Tree Insertion** for course IDs
- 🧾 Duplicate detection (USN and course ID level)
- 🧠 Simple and clean menu-driven UI

---

## 🛠️ Tech Stack

- Language: **C++**
- Concepts Used:
  - File I/O (ifstream, ofstream)
  - B-Tree (custom implementation)
  - String parsing and `stringstream`
  - Sets and Vectors
  - Command-line interface

---

## 📁 File Structure
├── main.cpp # Contains the entire application logic
├── courses.txt # Data file for student + course records
└── temp.txt # Used temporarily during delete/update


## 🔐 Admin Login Credentials

- **Username**: `admin`
- **Password**: `admin123`

---

## 🔄 Run
./student_app   # On Linux/Mac
student_app.exe # On Windows

## ▶️ How to Compile & Run

### 💻 Compile
Use any C++ compiler like `g++`:

```bash
g++ main.cpp -o student_app
```
## 📌 Sample Functionalities
## ✅ Admin Menu

1. Create Student Record
2. View Student Records
3. Search Student Record
4. Update Student Record
5. Delete Student Record
6. Logout

## ✅ Student Menu
1. Create Student Record
2. Logout

## 📘 Learnings
Implemented B-Trees manually for structured indexing

Built a basic record management system

Gained experience with file-based databases

Used C++ Standard Library features like set, vector, and fstream

Practiced user-friendly CLI design and error validation

## 📬 Contact
For queries or suggestions:

## ✉️ Email: mrnishanth07@gmail.com

## 🧑‍💻 GitHub: @NishanthGowda007
