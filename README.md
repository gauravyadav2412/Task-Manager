# Task-Manager[README.md](https://github.com/user-attachments/files/23731131/README.md)
# Task Manager (Python CLI)

A simple **command-line Task Manager** written in Python.\
This program lets you add, view, delete, save, and load tasks using a
text file (`tasks.txt`).\
Perfect for beginners learning Python file handling and basic menus.

## 🚀 Features

-   **Add tasks** interactively\
-   **View all tasks** with numbering\
-   **Delete tasks** by choosing task number\
-   **Save tasks** to a file (`tasks.txt`)\
-   **Load tasks** from the file\
-   Simple and beginner-friendly CLI menu

## 📂 File Structure

    ├── task_manager.py
    └── tasks.txt   (auto-created after saving)

## 📝 How It Works

The program stores tasks in a list named `tasks`.\
Using a text file allows the tasks to persist even after closing the
program.

### Main Functionalities:

-   `add_task()` → Add a new task\
-   `view_tasks()` → Display tasks\
-   `save_tasks()` → Save tasks to disk\
-   `load_tasks()` → Load tasks from disk\
-   `delete_task()` → Remove a task by number

## ▶️ How to Run

1.  Make sure Python 3 is installed.
2.  Run the script:

``` bash
python task_manager.py
```

3.  Use the menu to manage your tasks:

```{=html}
<!-- -->
```
    1 add
    2 save
    3 view
    4 delete
    5 load
    6 exit

## 📌 Example Usage

    1 add
    Enter a task: Buy groceries
    Task added

    3 view
    1 Buy groceries

## 💡 Future Improvements (Optional Ideas)

-   Add deadlines or priority levels\
-   Edit existing tasks\
-   JSON storage instead of plain text\
-   GUI version using Tkinter or PyQt\
-   Save automatically on exit

## 📜 License

This project is open-source. Feel free to modify and use it as you like.
