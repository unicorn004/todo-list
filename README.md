# To-Do List Application

This is a comprehensive to-do list application built using HTML, CSS, JavaScript, Python, and Django. The application allows users to manage their tasks effectively with features like categorization, due dates, priority levels, and reminders.

## Features

- **User Authentication**
  - Sign Up/Log In
  - Profile Management

- **Task Management**
  - Add Task
  - Edit Task
  - Delete Task
  - Mark as Complete

- **Advanced Features**
  - Categorize Tasks with Tags
  - Set Due Dates and Reminders
  - Assign Priority Levels
  - Search and Filter Tasks

- **User Interface Enhancements**
  - Drag and Drop for Task Reordering
  - Responsive Design for Mobile Compatibility

## Technologies Used

- **Frontend**
  - HTML
  - CSS (Bootstrap/Tailwind)
  - JavaScript

- **Backend**
  - Python
  - Django

## Installation

1. **Clone the repository, setup virtual environment, install dependencies, run migrations, and start the development server**
   ```sh
   git clone https://github.com/unicorn004/todo-list.git
   cd todo-list
   python -m venv venv               # Setup virtual environment (optional)
   venv\Scripts\activate             # On Windows
   source venv/bin/activate          # On macOS/Linux
   pip install -r requirements.txt   # Install dependencies
   python manage.py migrate          # Run migrations
   python manage.py runserver        # Start the development server
   
2. **Open your browser and navigate to: http://127.0.0.1:8000/**
