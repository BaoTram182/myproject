# 🚀 Task API Project

## 📌 Description

This project is built using Django REST Framework to manage tasks.

It allows users to perform full CRUD operations:

* Create tasks
* Read tasks
* Update tasks
* Delete tasks

## ✨ Features

* RESTful API design
* Task CRUD operations
* JWT Authentication
* Swagger API documentation
* Admin panel support

## 🛠 Tech Stack

* Python
* Django
* Django REST Framework
* SQLite (default database)

---

## ⚙️ Installation & Setup

### 1. Clone repository

git clone https://github.com/BaoTram182/myproject.git
cd myproject

### 2. Create virtual environment

python -m venv venv

### 3. Activate virtual environment

**Windows:**
venv\Scripts\activate

**Mac/Linux:**
source venv/bin/activate

### 4. Install dependencies

pip install -r requirements.txt

### 5. Run migrations

python manage.py migrate

### 6. Create superuser

python manage.py createsuperuser

### 7. Run server

python manage.py runserver

---

## 🌐 API

* Task list:
  http://127.0.0.1:8000/api/tasks/

* Swagger UI:
  http://127.0.0.1:8000/swagger/

---

## 🔐 Authentication (JWT)

This API uses JWT authentication.

### Get Access Token

POST /api/token/

Body:
{
"username": "your_username",
"password": "your_password"
}

### Refresh Token

POST /api/token/refresh/

Body:
{
"refresh": "your_refresh_token"
}

### Usage

Add this header to your requests:

Authorization: Bearer <your_access_token>

---

## 📦 Requirements

asgiref==3.11.1
Django==6.0.3
djangorestframework==3.17.1
drf-yasg==1.21.15
inflection==0.5.1
packaging==26.0
pytz==2026.1.post1
PyYAML==6.0.3
sqlparse==0.5.5
tzdata==2025.3
uritemplate==4.2.0

---

## 👤 Author

GitHub: https://github.com/BaoTram182

---

## 📝 Notes

* Run migrations before starting:
  python manage.py migrate

* If requirements.txt is missing:
  pip freeze > requirements.txt

---

## 🚀 Deployment (Optional)

You can deploy this project using:

* Render
* Railway
* PythonAnywhere
