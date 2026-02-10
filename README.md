# 🎓 Student Management System (DBMS Project)

A full-stack **Student Management System** developed as a **DBMS course project**, showcasing practical implementation of database concepts using a real-world application.

---

## 📌 Project Overview

This project is designed to manage academic data efficiently, including students, courses, teachers, departments, classrooms, and enrollments. It demonstrates proper **database design**, **relationships**, and **CRUD operations** integrated with a working frontend and backend.

---

## 🛠 Tech Stack

### Frontend
- React.js
- Axios
- React Router DOM
- CSS (Responsive UI)

### Backend
- Node.js
- Express.js
- JWT Authentication
- bcrypt.js

### Database
- MySQL
- MySQL Workbench

---

## ✨ Features

### 🔐 Authentication
- Login & Logout
- JWT-based authentication
- Secure password hashing

### 📚 Student Management
- Add, view, update, delete student records

### 📘 Course Management
- Manage course details

### 👩‍🏫 Teacher Management
- Add and manage teachers

### 📝 Enrollment Management
- Enroll students into courses
- Maintain relational integrity

### 🏢 Department Management
- Create and view departments

### 🏫 Classroom Management
- Manage classrooms

### 🎨 UI/UX
- Responsive design
- Form validation
- Clean and simple interface

---

## 🗂 Database Design (DBMS Concepts Used)

- Normalization
- Primary Keys
- Foreign Keys
- One-to-Many & Many-to-Many Relationships
- Referential Integrity
- SQL (DDL & DML)

### Entities
- Users
- Students
- Courses
- Teachers
- Enrollments
- Departments
- Classrooms

---
## 📁 Project Structure

student-management/
│
├── backend/
│   ├── src/
│   │   ├── app.js
│   │   ├── db/
│   │   │   └── db.js
│   │   └── routes/
│   │       ├── auth.js
│   │       ├── students.js
│   │       ├── courses.js
│   │       ├── teachers.js
│   │       ├── enrollments.js
│   │       ├── departments.js
│   │       └── classrooms.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
│   ├── public/
│   └── package.json
│
├── screenshots/
│   └── project-structure.png
│
└── README.md

---

## ⚙️ Setup Instructions

### 🔹 Prerequisites
- Node.js (v18 or above)
- MySQL (v8 or above)
- MySQL Workbench
- VS Code

---

### 🔹 Database Setup
1. Open MySQL Workbench
2. Create a new database
3. Run the SQL scripts to create tables and relationships

```sql
USE student_management;
SHOW TABLES;

