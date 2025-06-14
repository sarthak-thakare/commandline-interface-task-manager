# CLI Task Manager

A simple, interactive, and colorful command-line task manager built in C++.  
Supports adding, editing, completing, deleting, and exporting tasks — all from your terminal!

---

## Features

- Add tasks with **title**, **due date**, and **priority**
- View pending and completed tasks in a **clean table format**
- Edit task details (title, due date, priority)
- Delete single or **all tasks with confirmation**
- Mark tasks as completed
- Search tasks by keyword
- Show reminders for **today** and **tomorrow**
- Export tasks to a `tasks.md` markdown file
- Automatically loads/saves from `tasks.csv`
- Gracefully saves tasks on Ctrl+C (SIGINT)

---

##  Files

| File        | Purpose                         |
|-------------|---------------------------------|
| `main.cpp`  | Source code for task manager    |
| `tasks.csv` | Stores tasks persistently       |
| `tasks.md`  | Markdown export of task list    |

---

## Compile:
```bash g++ main.cpp -o tasker
