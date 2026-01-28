# Online Journal Web Platform

A web-based platform for creating, managing, and publishing online journal articles.

The project was developed as part of a **Bachelor Qualification Work** and demonstrates full-stack web development using **Django** and **PostgreSQL**.

---

## 📌 Overview

The **Online Journal Web Platform** allows users to register, authenticate, and manage journal articles through a user-friendly web interface.

The system supports:
- role-based access control,
- content creation and management features,

making it suitable for **personal blogging** or **small editorial platforms**.

The project follows the **Django MTV (Model–Template–View)** architectural pattern and focuses on:
- clean project structure,
- scalability,
- maintainability.

---

## 🎯 Features

- User registration and authentication  
- Role-based access control (users and administrators)  
- Create, edit, and delete journal articles  
- Article organization and structured content handling  
- Responsive user interface  
- Secure interaction with the database  

---

## 🛠 Technologies Used

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** PostgreSQL  
- **Version Control:** Git, GitHub  

---

## 🏗 Architecture

The application is built using the **Django MTV (Model–Template–View)** architecture:

- **Models** — define the database structure and business entities  
- **Templates** — handle data presentation and UI rendering  
- **Views** — implement business logic and user interaction  

This approach ensures a clear separation of concerns and improves long-term maintainability.

---

## 🗄 Database

**PostgreSQL** is used as the primary relational database management system.

The database stores:
- user accounts,
- journal articles,
- related metadata.

All database interactions are handled via **Django ORM**, ensuring data integrity and security.

---

## ⚙ Installation (Local Setup)

### 1️⃣ Clone the repository

    git clone https://github.com/bohdan-zhemelko/django-online-journal.git
    cd django-online-journal

### 2️⃣ Create and activate a virtual environment

    python -m venv venv
    source venv/bin/activate    # Linux / macOS
    venv\Scripts\activate       # Windows

### 3️⃣ Install dependencies

    pip install -r requirements.txt

### 4️⃣ Configure environment variables

- Database credentials  
- Django secret key  

### 5️⃣ Run migrations and start the server

    python manage.py migrate
    python manage.py runserver

The application will be available at:

    http://127.0.0.1:8000/

---

## 🎓 Project Purpose

This project was developed for **educational purposes** to demonstrate:

- Web application architecture  
- Backend and frontend integration  
- Database-driven web development   
