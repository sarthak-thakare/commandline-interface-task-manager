#  CLI Task Manager (C++)

A command-line based task manager built in C++ that lets you add, view, edit, search, and complete tasks — all stored persistently in a CSV file.

##  Features

- Add tasks with title, due date, and priority
- List pending tasks, sorted by due date and priority
- Mark tasks as completed
- View completed task history
- Search tasks by keyword
- Edit task title, due date, or priority
- Save/load tasks from a `.csv` file
- Color-coded CLI and formatted output for readability
- Command help menu

---

##  Technologies Used

- Language: C++17
- File I/O: CSV file for persistent storage
- CLI Styling: ANSI escape codes + `<iomanip>`
- Version Control: Git

---

##  How to Build

### Requirements
- A C++17 compatible compiler (`g++` recommended)
- Git (optional, for cloning)

### Compile
```bash
g++ -std=c++17 main.cpp -o taskmgr
