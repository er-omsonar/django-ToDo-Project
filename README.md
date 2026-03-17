# 📝 Django To-Do App

🔗 **Live Demo:** https://django-todo-project-ksaq.onrender.com/

## 🚀 Project Overview

This is a simple yet powerful To-Do web application built using **Django**.  
It helps users manage their daily tasks effectively with a clean and intuitive interface.

The app allows users to add tasks, mark them as completed, move them back to pending, edit tasks, and delete them easily.

---

## ✨ Features

- ➕ Add new tasks using input field or keyboard
- 📋 View all pending tasks in the Task section
- ✅ Mark tasks as completed
- 🔄 Move completed tasks back to pending (Mark as Undone)
- ✏️ Edit existing tasks
- ❌ Delete tasks anytime
- 🎯 Clean UI with separate sections for:
  - Pending Tasks
  - Completed Tasks

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default Django DB)

---

## 📂 Project Functionality

- When a user adds a task → it appears in the **Task Section**
- Clicking **Mark as Done** → moves task to **Completed Section**
- Clicking **Mark as Undone** → moves task back to **Task Section**
- Tasks can be edited or deleted at any time

---

## 📸 Screenshots (Optional)

_Add screenshots here if you want to showcase UI_

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate into the project folder
cd your-repo-name

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run server
python manage.py runserver


🎯 What I Learned

Django project structure and app management

CRUD operations (Create, Read, Update, Delete)

Handling user input and form submission

Working with Django models and database

Implementing task status logic (Done / Undone)

Improving UI/UX with Bootstrap

🔗 Live Project

👉 https://django-todo-project-ksaq.onrender.com/
