# 🏥 Clinic Booking System API

A simple RESTful API for managing patients, doctors, and appointments in a clinic. Built using **FastAPI**, **SQLAlchemy**, and **SQLite**.

---

## 🚀 Features

* ✅ **Patient Management:** Create, retrieve, update, and delete patient records.
* 🔮 **Future-Ready:** Designed to easily extend for doctor and appointment management.
* 🗄️ **ORM Integration:** Full database setup using SQLAlchemy ORM.
* 📄 **Auto-Documentation:** Interactive API docs generated via Swagger UI and ReDoc.

---

## 🔧 Technologies Used

[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)](https://www.sqlalchemy.org/)
[![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)](https://docs.pydantic.dev/)

* **FastAPI:** For building APIs quickly and efficiently.
* **SQLAlchemy:** For ORM-based database interactions.
* **SQLite:** As the database for simplicity.
* **Pydantic:** For request validation and response serialization.

---

## 🗄️ Database & Diagrams

### SQL Script
The `create_database.sql` file contains the SQL code used to create the database tables manually.

### 📊 ERD (Entity-Relationship Diagram)
You can view the ERD diagram here:
📎 **[View Database Diagram](https://1drv.ms/i/c/2bb2f9afc8ae1149/EZTv_XSFX1VCu8FN44OHd5wBH-S861J8-p6PwUCHFFhJZQ?e=qLY05R)**

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/Cynthia-M-M/clinic-booking-system-api.git](https://github.com/Cynthia-M-M/clinic-booking-system-api.git)

cd clinic-booking-system-api

```

### 2. Set Up Virtual Environment

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate

```

**Mac/Linux:**

```bash
python3 -m venv venv
source venv/bin/activate

```

### 3. Install Dependencies

```bash
pip install fastapi uvicorn sqlalchemy

```

*(Or if you have a requirements file: `pip install -r requirements.txt`)*

---

## 🏃‍♂️ How to Run

Start the development server using Uvicorn:

```bash
uvicorn main:app --reload

```

> The server will start at `http://127.0.0.1:8000`

---

## 📄 API Documentation

FastAPI automatically generates interactive documentation for your API. Once the server is running, you can access:

* **Swagger UI (Interactive):** [http://127.0.0.1:8000/docs](https://www.google.com/url?sa=E&source=gmail&q=http://127.0.0.1:8000/docs)
* **ReDoc (Alternative):** [http://127.0.0.1:8000/redoc](https://www.google.com/search?q=http://127.0.0.1:8000/redoc)

---

## 📂 Project Structure

```text
clinic-booking-system-api/
│
├── main.py             # Entry point (API routes)
├── database.py         # Database connection & session setup
├── models.py           # SQLAlchemy database models
├── schemas.py          # Pydantic models (data validation)
├── create_database.sql # Manual SQL script
└── README.md           # Project documentation

```

---

## 🔗 Key Endpoints

| Method | Endpoint | Description |
| --- | --- | --- |
| `POST` | `/patients/` | Create a new patient |
| `GET` | `/patients/` | Get a list of all patients |
| `GET` | `/patients/{id}` | Get details of a specific patient |
| `PUT` | `/patients/{id}` | Update patient information |
| `DELETE` | `/patients/{id}` | Remove a patient record |

---

## 📄 License

This project is open-source and available for educational purposes.

```

```
