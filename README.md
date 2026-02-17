# 🎓 Student Management System — Django

A full-stack **Student Management System** built with Django that enables educational institutions to manage students, staff, courses, attendance, academic results, and administrative workflows through a secure, role-based web application.

This project demonstrates practical implementation of Django authentication, permissions, dashboards, and scalable application design.

---

## 📖 Overview

The Student Management System centralizes academic and administrative operations within a single platform. It supports three user roles — **Admin (HOD)**, **Staff**, and **Students** — each with dedicated dashboards and role-specific permissions.

The system is designed following Django best practices, including modular architecture, secure authentication, and maintainable code structure.

---

## ✨ Features

### Core Features

* Role-based authentication (Admin / Staff / Student)
* Email-based login system
* Secure password management
* Responsive dashboard interface (AdminLTE)
* Profile management for all users

### Academic Management

* Course, subject, and academic session management
* Attendance tracking and updates
* Student result creation and publishing
* Performance summaries and analytics

### Workflow Management

* Leave request and approval system
* Feedback submission and response mechanism
* Optional Firebase Web Push notifications
* Google CAPTCHA integration

---

## 👥 User Roles

### Admin (HOD)

* Institutional analytics dashboard
* Manage students, staff, courses, subjects, and sessions
* Monitor attendance records
* Approve or reject leave requests
* Respond to feedback
* Edit admin profile

### Staff / Teachers

* Subject-based dashboard insights
* Take and update student attendance
* Add and update student results
* Apply for leave
* Send feedback to HOD
* Edit staff profile

### Students

* Personal academic dashboard
* View attendance and results
* Apply for leave
* Submit feedback
* Edit student profile

---

## 🛠 Tech Stack

**Backend**

* Python
* Django

**Frontend**

* HTML5, CSS3
* Bootstrap
* AdminLTE Template

**Database**

* SQLite (default)
* Compatible with PostgreSQL and MySQL for production use

**Security & Authentication**

* Email-based authentication
* Role-based access control
* CSRF protection
* Django middleware permissions

---

## 📸 Screenshots

Screenshots for Admin, Staff, and Student dashboards are available in the `ss/` directory.

---

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.9 or higher
* Git
* pip (Python package manager)
* Virtual environment support

---

### 1. Clone the Repository

```bash
git clone https://github.com/ashoknepalofficial/StudentManagementSystemUsingDjango.git
cd StudentManagementSystemUsingDjango
```

---

### 2. Create and Activate Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Configure Allowed Hosts

Edit `settings.py`:

```python
ALLOWED_HOSTS = []
```

⚠️ Do not use wildcard (`*`) hosts in production.

---

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

---

### 6. Create Superuser

```bash
python manage.py createsuperuser
```

---

### 7. Run Development Server

```bash
python manage.py runserver
```

Access the application at:

```
http://127.0.0.1:8000/
```

---

## 🔐 Default Test Credentials (Optional)

| Role    | Email                                             | Password |
| ------- | ------------------------------------------------- | -------- |
| Admin   | [admin@admin.com](mailto:admin@admin.com)         | admin    |
| Staff   | [staff@staff.com](mailto:staff@staff.com)         | staff    |
| Student | [student@student.com](mailto:student@student.com) | student  |

⚠️ These credentials are for local testing only. Remove or change them before deploying.

---

## 🔒 Security Recommendations

* Change all default credentials
* Use environment variables for secrets and database credentials
* Enable HTTPS in production
* Configure proper database permissions
* Disable debug mode in production
* Secure email credentials properly

---

## 🚀 Deployment

This project can be deployed on:

* VPS (Ubuntu + Gunicorn + Nginx)
* Heroku
* Railway
* Render
* Docker (recommended for production)

If needed, production deployment documentation or Docker setup can be added.

---

## 📜 License

This project is intended for educational and demonstration purposes.
You are free to use, modify, and extend it.
=======
# StudentManagementSystemUsingDjango
A role-based Student Management System built with Django for managing students, staff, attendance, results, and academic workflows.
>>>>>>> 021ee5bb24a1e1bdbd53e272386d6e365688ac0a
