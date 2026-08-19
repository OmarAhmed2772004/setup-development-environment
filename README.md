# 🚀 Setup Development Environment & Projects RESTful API

A robust, production-ready Node.js & Express RESTful API integrated with MongoDB Atlas. This project serves as a foundational backend service demonstrating clean architecture, database integration, environment variables security, and full CRUD operations.

---

## 🛠️ Tech Stack & Tools

* **Backend Environment:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB Atlas (Cloud)
* **ODM:** Mongoose
* **Environment Management:** Dotenv
* **Development Utility:** Nodemon
* **Version Control:** Git & GitHub

---

## ✨ Features

* **Cloud Database Integration:** Secure connection to MongoDB Atlas.
* **RESTful CRUD Endpoints:** Full capabilities to Create, Read, Update, and Delete projects.
* **Data Validation:** Strict schema validation via Mongoose.
* **Environment Security:** Sensitive configurations isolated using `.env`.
* **Standard HTTP Responses:** Proper status codes and structured JSON responses (`200`, `201`, `400`, `404`, `500`).

---

## 🔗 API Endpoints

| Method | Endpoint | Description | Status Code |
| :--- | :--- | :--- | :--- |
| `GET` | `/api/projects` | Retrieve all projects | `200 OK` |
| `GET` | `/api/projects/:id` | Retrieve a single project by ID | `200 OK` / `404 Not Found` |
| `POST` | `/api/projects` | Create a new project | `201 Created` / `400 Bad Request` |
| `PUT` | `/api/projects/:id` | Update an existing project | `200 OK` / `400 Bad Request` |
| `DELETE`| `/api/projects/:id` | Delete a project | `200 OK` / `404 Not Found` |

---

## 📥 Sample Request Body (POST/PUT)

```json
{
  "title": "E-Commerce Backend API",
  "description": "Full REST API with authentication and database integration.",
  "technologies": ["Node.js", "Express", "MongoDB"],
  "githubUrl": "[https://github.com/OmarAhmed2772004/setup-development-environment](https://github.com/OmarAhmed2772004/setup-development-environment)"
}
