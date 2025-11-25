Smart CLI To-Do Manager – Python
-> A minimal, powerful, and persistence-driven task manager built using pure Python for developers who love clarity and productivity.


Project Overview
-> Smart CLI To-Do Manager is a lightweight yet efficient command-line application that helps you organize your daily tasks with ease. It focuses on clean architecture, reliability, and simplicity while maintaining persistent storage.

This project is ideal for showcasing:
Python fundamentals
File handling using JSON
Real-world CRUD operations
Input validation & user experience design

Features
✅ Add new tasks
📋 View all tasks with status indicators
✅ Mark tasks as completed
🗑️ Delete tasks easily
💾 Persistent task storage using JSON
🛡️ Error handling for invalid inputs
⚡ Fast and responsive CLI interaction

How It Works
Tasks are stored in a local tasks.json file
Each task contains:
    title – Task description
    done – Completion status (true/false)
Data is automatically saved after every update

Sample Data Structure:
json:
{
  "title": "Learn FastAPI",
  "done": false
}

Interface Preview
==== SIMPLE TO-DO APP ====
1. Show tasks
2. Add task
3. Mark task as done
4. Delete task
5. Exit

Tech Stack:
Python 3.x
JSON for data persistence
Standard Libraries:
json
os

Installation & Usage:
1️)Clone the repository
-> git clone https://github.com/bikas-yadav/CLI-based-To-Do-Application.git
   cd todo-cli-python

2️)Run the application
-> python main.py

Project Structure:
todo-cli-python/
│
├── main.py        # Main application logic
├── tasks.json     # Auto-generated task storage
└── README.md      # Project documentation

Why This Project Stands Out:
  Clean, beginner-to-advanced readable code
  Practical real-world use case
  Demonstrates disciplined programming habits
  Easily extensible for GUI / Web versions
  Perfect showcase for Python CLI skills

Future Enhancements:
  Due date & priority system
  Task categories / tags
  Search and filter tasks
  GUI version using Tkinter
  Web app using FastAPI

⭐ Support
If you find this project useful, feel free to ⭐ the repository and share feedback!
