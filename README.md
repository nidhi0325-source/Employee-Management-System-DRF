# Employee Management System using Django REST Framework

##  Project Overview
This project is a backend **Employee Management System** built using **Django** and **Django REST Framework (DRF)**.  
It provides RESTful APIs to manage employee records and supports full CRUD operations with authentication and authorization.

The system is designed with a clear separation of backend logic and can be easily integrated with any frontend (React, Angular, mobile apps, etc.).

---

##  Features
- Employee record management (Create, Read, Update, Delete)
- RESTful API endpoints using Django REST Framework
- Secure authentication and authorization
- Django Admin panel for easy data management
- JSON-based API responses
- Clean project structure following best practices
- Version-controlled using Git and GitHub

---

## 🛠️ Technologies Used
- Python
- Django
- Django REST Framework
- SQLite (for development)
- Git & GitHub

---

## 📂 Project Structure
employee_system/
│
├── employee_app/
│ ├── models.py
│ ├── serializers.py
│ ├── views.py
│ ├── urls.py
│ └── admin.py
│
├── employee_system/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── manage.py
└── README.md



---

## 🔗 API Endpoints
| Method | Endpoint | Description |
|------|---------|-------------|
| GET | /api/employees/ | List all employees |
| POST | /api/employees/ | Add new employee |
| GET | /api/employees/{id}/ | Retrieve employee |
| PUT | /api/employees/{id}/ | Update employee |
| DELETE | /api/employees/{id}/ | Delete employee |

---

##  How to Run the Project
1. Clone the repository
git clone https://github.com/nidhi0325-source/Employee-Management-System-DRF.git

2. Navigate to project directory
cd employee_system

3.Create and activate virtual environment
python -m venv venv
venv\Scripts\activate

4.Install dependencies
pip install django djangorestframework

5. Run migrations
python manage.py migrate

6. Start server
python manage.py runserver

7. Open browser
http://127.0.0.1:8000/api/employees/
