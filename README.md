# 📋 CRM System

A simple Customer Relationship Management (CRM) web application built using Django. This project allows users to manage customer records, add new records, update existing ones, and view details in a user-friendly interface.

---

## 🧠 Features
- User registration and authentication
- Add, update, and delete customer records
- View detailed information for each record
- Responsive web interface with navigation bar

---

## 🛠️ Tech Stack
- Python 3.12+
- Django (web framework)
- MySQL (database, can be changed)
- HTML, CSS (templates)

---

## 🗂️ Project Structure
```
CRMsystem/
├── manage.py
├── mydb.py
├── README.md
├── crm/                 # Django project configuration files
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__/
├── website/             # Main app containing models, views, forms, templates, and migrations
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── __pycache__/
│   ├── migrations/
│   └── templates/
│       ├── add_record.html
│       ├── base.html
│       ├── home.html
│       ├── navbar.html
│       ├── record.html
│       ├── register.html
│       └── update_record.html
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.12+
- Django (see requirements below)

### Installation
1. Clone the repository:
	```powershell
	git clone https://github.com/anushka-1205/CRMsystem.git
	```
2. Navigate to the project directory:
	```powershell
	cd CRMsystem
	```
3. Install dependencies:
	```powershell
	pip install django
	```
4. Apply migrations:
	```powershell
	python manage.py migrate
	```
5. Run the development server:
	```powershell
	python manage.py runserver
	```
6. Open your browser and go to `http://127.0.0.1:8000/`

---
Author: Anushka Srivastava
