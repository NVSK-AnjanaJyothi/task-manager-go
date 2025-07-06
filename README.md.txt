# 🧠 Task Manager API - Built with Go + SQLite

This is a simple backend API that allows users to **create**, **view**, **update**, and **delete** tasks (CRUD operations).  
It’s built using **Golang**, **SQLite**, and the **Gorilla Mux** router.

---

## 🚀 Features

- Create new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Uses SQLite database (no external server required)

---

## 📦 Technologies Used

- 🟨 Golang (Go)
- 🐒 Gorilla Mux
- 🗂 SQLite (with modernc.org/sqlite driver)

---

## 📁 API Endpoints

| Method | Endpoint        | Description         |
|--------|------------------|---------------------|
| GET    | `/tasks`         | Get all tasks       |
| POST   | `/tasks`         | Create new task     |
| PUT    | `/tasks/{id}`    | Update a task       |
| DELETE | `/tasks/{id}`    | Delete a task       |

---

## 🧪 Example API Usage (with Postman)

### ✅ Create Task
POST http://localhost:8081/tasks


**Body (JSON):**
```json
{
  "title": "Learn Go",
  "completed": false
}

GET http://localhost:8081/tasks
{
  "title": "Learn Go + SQLite",
  "completed": true
}

DELETE http://localhost:8081/tasks/1




✅ Make sure you have Go installed and internet access for downloading dependencies.



