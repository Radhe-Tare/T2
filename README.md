# To-Do List Manager

A simple command-line based To-Do List Manager written in Python. It allows users to add, view, and remove tasks with persistent storage using a local text file.

---

## Features

* 📅 Persistent task storage (`tasks.txt`)
* ➕ Add new tasks
* ✅ View existing tasks
* ❌ Remove tasks by number
* ⏹ Exit option to terminate program

---

## Getting Started

### Prerequisites

* Python 3.x installed

### Running the Program

```bash
python todo.py
```

---

## Usage

Upon running, you'll see the following options:

```
To-Do List Manager
1. View tasks
2. Add task
3. Remove task
4. Exit
```

### Example Flow

```
Choose an option: 2
Enter new task: Buy groceries
Added: Buy groceries

Choose an option: 1
1. Buy groceries

Choose an option: 3
1. Buy groceries
Enter task number to remove: 1
Removed: Buy groceries

Choose an option: 4
Goodbye!
```

---

## File Structure

```
todo.py
README.md
tasks.txt (auto-created when needed)
```

---

## Notes

* Tasks are stored in `tasks.txt`, one per line.
* The program automatically handles file creation.
* Error handling is included for invalid input and task number ranges.

---

## Future Improvements

* Add deadlines or priorities
* Mark tasks as completed
* Export/import task lists
* GUI version using Tkinter

---

## Author

Created with simplicity by Radhe Tare
