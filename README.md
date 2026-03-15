# 📚 Scientific Publications Platform — Backend

Backend service for the **Scientific Publications Management Platform**, developed for the **Enterprise Application Development (DAE)** course.

The backend is responsible for handling the **business logic, data persistence, and REST API** used by the frontend application. 

---

## 🚀 Features

* User authentication and role management
* Upload and management of scientific publications
* Tagging and classification of publications
* Comments and ratings system
* Search and filtering of publications
* User activity history
* Email notifications for subscribed tags

---

## 🛠 Technologies

* **Jakarta EE**
* **REST API**
* **PostgreSQL**
* **ORM / Persistence layer**
* **Docker (AI summarization service)** 

---

## 🏗 Architecture

The backend follows a layered architecture:

* **REST Controllers** – expose API endpoints
* **Service Layer** – business logic
* **Persistence Layer** – database access
* **Database** – relational storage of publications, users and tags

---

## ⚙️ API

The backend exposes a **RESTful API** that allows the frontend to:

* Manage users
* Upload and retrieve publications
* Add comments and ratings
* Search publications
* Manage tags and subscriptions

All endpoints return **JSON responses**.

---

## 🧠 AI Integration

The system includes AI features such as:

* Automatic generation of **publication summaries**

This functionality runs inside a **Docker container with an LLM service**, accessed through an API client implemented in the backend. 

---

## 👩‍💻 Authors

Developed by Tatiana Frade, Rafael Coelho, Duarte Pereira, José Fernandes 
