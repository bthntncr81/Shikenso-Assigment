# 🧠 Backend – FastAPI To-Do API

This is the backend for the To-Do List Management System, built using **FastAPI**, **SQLAlchemy**, and **SQLite**.

---

## ✅ Features

- ✅ Get all to-do items
- ✅ Create a new to-do item
- ✅ Update an existing item
- ✅ Delete an item
- ✅ File-based SQLite DB for persistence
- ✅ CORS enabled for frontend integration

---

## 📦 Tech Stack

- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn (ASGI server)

---

## 🚀 Getting Started

### 1. Clone the project

```bash
cd todo-backend
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

---

## ✅ `todo-frontend/README.md`

````markdown
# 🎨 Frontend – Angular To-Do App

This is the frontend for the To-Do List Management System, built using **Angular 17**, **SCSS**, and **Reactive Forms**.

---

## ✅ Features

- ✅ Display list of to-do items
- ✅ Add new item via form
- ✅ Mark item as completed/incomplete
- ✅ Delete an item
- ✅ Filter: All / Completed / Open
- ✅ Search by title
- ✅ Sort by due date
- ✅ Routing between list and add form

---

## 🌐 Angular Modules Used

- `HttpClientModule`
- `FormsModule`
- `ReactiveFormsModule`
- `RouterModule`

---

## 🚀 Getting Started

### 1. Navigate to frontend

```bash
cd todo-frontend
npm install
ng serve
```
````
