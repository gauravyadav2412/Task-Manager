# Task Manager -- Project Specification

## 1. Program Statement

The **Task Manager** is a command-line Python application designed to
help users manage their daily tasks efficiently.\
It allows users to add, view, delete, save, and load tasks using a
simple text-based interface. The program stores tasks in a list and
saves them to a local file (`tasks.txt`) to maintain persistence across
sessions.

## 2. Scope of the Project

### In Scope

-   Adding new tasks\
-   Displaying all current tasks\
-   Deleting tasks by index\
-   Saving tasks to a text file\
-   Loading tasks from a text file\
-   Simple, easy-to-understand CLI interface\
-   Basic error handling for invalid input

### Out of Scope

-   Task deadlines, priority levels, categories\
-   User authentication\
-   Multi-user support\
-   GUI or web interface\
-   Automatic cloud sync\
-   Database support (SQL/NoSQL)

## 3. Target Users

### ✔ Students

### ✔ Beginners Learning Python

### ✔ Individuals Wanting a Simple To-Do Tool

### ✔ Developers Practicing Small Projects

## 4. System Requirements

-   Python 3.x\
-   Works on Windows, Linux, and macOS\
-   No additional libraries required

## 5. Objectives of the Project

-   Create a functional command-line task manager\
-   Practice CRUD operations\
-   Learn file handling in Python\
-   Implement error-safe user input handling\
-   Maintain persistent task data

## 6. Technologies Used

-   Python\
-   Text file (`tasks.txt`)\
-   CLI interface\
-   Git (optional)

## 7. Functional Requirements

-   FR1: Add a task\
-   FR2: Display all tasks\
-   FR3: Delete a task\
-   FR4: Save tasks\
-   FR5: Load tasks\
-   FR6: Continuous menu loop

## 8. Non-Functional Requirements

-   Usability\
-   Portability\
-   Reliability\
-   Efficiency\
-   Maintainability

## 9. Constraints

-   Single-user\
-   Plain text storage\
-   Basic error handling\
-   Index-based deletion\
-   No multi-device sync

## 10. Expected Output

    1 add
    Enter a task: Buy groceries
    Task added

    3 view
    1 Buy groceries

    2 save
    Saved

    6 exit
    bye

## 11. Future Expansion Possibilities

-   Task priorities\
-   Deadlines & reminders\
-   JSON or CSV storage\
-   GUI version\
-   REST API\
-   Mobile or web app
