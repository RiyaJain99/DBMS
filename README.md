🎓 Student Management System (DBMS Project)

A full-stack Student Management System built as part of a DBMS course project, designed to manage students, courses, teachers, enrollments, departments, and classrooms efficiently using a relational database.

📌 Project Overview

This project demonstrates the practical implementation of Database Management Systems (DBMS) concepts using a real-world application. It includes:

Proper database schema design

CRUD operations on multiple entities

Relational integrity using foreign keys

A working backend API

A user-friendly frontend interface

🛠 Tech Stack
Frontend

React.js

Axios

React Router DOM

CSS (Modern UI with responsive design)

Backend

Node.js

Express.js

JWT Authentication

bcrypt (password hashing)

Database

MySQL (Relational Database)

MySQL Workbench

✨ Features
🔐 Authentication

User Login & Logout

JWT-based authentication

Secure password hashing

📚 Student Management

Add, view, update, delete students

📘 Course Management

Add, view, update, delete courses

👩‍🏫 Teacher Management

Add, view, update, delete teachers

📝 Enrollment Management

Enroll students into courses

Maintain relational integrity

🏢 Department Management

Create and view departments

🏫 Classroom Management

Create and view classrooms

🎨 UI/UX

Responsive design

Modal popups

Form validation

Hover effects and animations

🗂 Database Design (DBMS Concepts Used)

Normalization

Primary Keys

Foreign Keys

One-to-Many & Many-to-Many relationships

Referential Integrity

SQL Queries (DDL & DML)

Entities include:

Users

Students

Courses

Teachers

Enrollments

Departments

Classrooms





PROJECT STRUCTURE->

student-management/
│
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── students.js
│   │   ├── courses.js
│   │   ├── teachers.js
│   │   ├── enrollments.js
│   │   ├── departments.js
│   │   └── classrooms.js
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.css
│   └── package.json
│
└── README.md
