# Backend – FastAPI To-Do API

This directory contains the backend for the To-Do List Management System. It is built with FastAPI and SQLAlchemy, using SQLite for data storage. The backend exposes a RESTful API to be consumed by the Angular frontend.

## Features

- List all to-do items
- Add a new to-do item
- Update an existing to-do item
- Delete a to-do item
- File-based SQLite database
- CORS enabled for frontend integration

## Tech Stack

- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

## Getting Started

````bash
cd todo-backend
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload



---

### ✅ `todo-frontend/README.md`

```markdown
# Frontend – Angular To-Do Application

This directory contains the frontend for the To-Do List Management System, built with Angular 17. It interacts with the FastAPI backend to manage task items.

## Features

- Display to-do items
- Add new items via a form
- Mark items as complete or incomplete
- Delete items
- Filter: All / Completed / Open
- Search by title
- Sort by due date (ascending/descending)
- Page routing between list and form views

## Angular Modules Used

- HttpClientModule
- FormsModule
- ReactiveFormsModule
- RouterModule

## Getting Started

```bash
cd todo-frontend
npm install
ng serve
````
