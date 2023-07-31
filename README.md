# To Do App with Django

## Project Description:

This is a simple To Do application built with Django. It allows users to create, edit, and delete tasks in a to-do list.

## System Requirements:

## Before running the project, make sure you have the following requirements installed on your machine:
- Python 3.x
- Django
- MyEnv

## Installation:

Follow the steps below to set up and run the project locally:

### 1. Clone the repository
```
git clone https://github.com/Gincaza/ToDo-App
```

### 2. Set up the virtual environment (recommended)

Create and activate a virtual environment using `virtualenv` to isolate project dependencies:

#### On macOS and Linux:
```
python3 -m venv venv
source venv/bin/activate
```
#### On Windows:
```
python -m venv venv
venv\Scripts\activate
```
#### 3. Apply migrations

Before starting the server, you need to apply Django migrations to create the database:
```
python manage.py migrate
```
#### 4. Start the development server

Now, you can start the Django development server:
```
python manage.py runserver
```
The server will be available at http://localhost:8000/.
