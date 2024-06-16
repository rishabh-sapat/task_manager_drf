# Task Manager

A simple Django application to manage tasks with a RESTful API.

## Requirements

- Django
- Django REST Framework

## Setup

1. Clone the repository:
   git clone <repository_url>
   cd taskmanager

2. Install dependencies:
   pip install -r requirements.txt

3. Apply migrations:
   python manage.py migrate

4. Run the server:
   python manage.py runserver

5. Open your browser and go to:
   http://127.0.0.1:8000

## API Endpoints

- `GET /api/tasks/` - List all tasks
- `POST /api/tasks/` - Create a new task
- `GET /api/tasks/<id>/` - Retrieve a task
- `PUT /api/tasks/<id>/` - Update a task
- `DELETE /api/tasks/<id>/` - Delete a task


