🚀  Smart To-Do List

NextUp is a desktop task management application built with C++, Qt 6, and custom Data Structures. It helps users organize tasks using a priority-based system, making sure the most important tasks are completed first.

This project was developed as a Data Structures course project to demonstrate the practical use of linked lists, priority queues, stacks, and file handling in a real-world application.

✨ Features
➕ Add new tasks with priorities
⭐ Automatic priority-based task management
✅ Complete the highest-priority task
↩️ Undo completed tasks
📋 Display all tasks
🔄 Sort tasks by priority
💾 Save tasks for future sessions
🖥️ Clean and modern Qt GUI
🛠️ Data Structures Used

This project was intentionally built without relying on STL containers for its core functionality.

Data Structure	Purpose
Priority Queue	Always retrieves the highest-priority task first
Linked List	Stores and manages task information
Stack	Supports the Undo feature
File Handling	Saves and loads tasks between sessions
🖥️ Technologies
C++
Qt 6
CMake
Data structure
📁 Project Structure
NextUp/
│
├── main.cpp
├── mainwindow.cpp
├── mainwindow.h
├── mainwindow.ui
│
├── PriorityQueue.h
├── PriorityQueue.cpp
│
├── LinkedList.h
├── LinkedList.cpp
│
├── Stack.h
├── Stack.cpp
│
├── FileManager.h
├── FileManager.cpp
│
├── Task.h
├── Colors.h
│
├── logo.ico
└── CMakeLists.txt
⚙️ How It Works
The user adds tasks and assigns priorities.
Tasks are stored in the linked list.
The priority queue determines which task should be completed first.
Completed tasks are pushed onto a stack.
The Undo operation restores the most recently completed task.
Tasks are automatically saved and loaded using file handling.
🚀 Getting Started
Prerequisites
Qt 6.5 or later
CMake 3.19+
C++17 compatible compiler
Build
git clone https://github.com/your-username/NextUp.git

cd NextUp

mkdir build
cd build

cmake ..
cmake --build .

Open the generated project in Qt Creator or your preferred IDE and run the application.

📚 Concepts Demonstrated
Object-Oriented Programming
Custom Data Structures
Priority Scheduling
File Persistence
GUI Development with Qt
CMake Project Configuration
🎯 Learning Objectives

This project demonstrates how classic data structures can be integrated into a practical desktop application instead of being implemented only as standalone algorithms.

👥 Authors

Developed as a university Data Structures project.

📄 License

This project is intended for educational purposes.
