# Django To-Do List Application

## Overview

This repository contains a Django project designed to create a to-do list application. It includes functionalities for adding, updating, and deleting tasks.

## Purpose

The purpose of this repository is to demonstrate how to build a task management system using Django, providing a practical example of CRUD (Create, Read, Update, Delete) operations.

## Technologies Used
- **Django**: A high-level Python web framework.
- **SQLite**: A lightweight database engine.
- **HTML/CSS**: For structuring and styling the web pages.
- **Python**: Back-end programming language.

## Project Structure
- **todo_project**: Contains models, views, templates, and static files for the to-do application.
- **db.sqlite3**: SQLite database file.
- **manage.py**: Django's command-line utility.

# Getting Started
### Prerequisites
- Python 3.x
- Django 3.x

### Installation
1. Clone the repository:
```bash
git clone https://github.com/duhajarrar/Django-ToDo-App.git
```

2. Navigate to the project directory and install dependencies:
```bash
cd todo_project
pip install -r requirements.txt
```
3. Apply migrations and run the server:
```bash
python manage.py migrate
python manage.py runserver
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
