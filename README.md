# 📚 Library Management System

A full-stack Library Management System built using **Java Spring Boot**, **Thymeleaf**, and **MySQL**, with support for multiple user roles (Admin, Librarian, Student), book management, and book issuing/return functionality.

---

## 🔧 Tech Stack

- **Backend:** Java 17, Spring Boot 3+, Spring MVC, Spring Security
- **Frontend:** Thymeleaf, HTML/CSS, Bootstrap
- **Database:** MySQL, Spring Data JPA, Hibernate
- **Build Tool:** Maven

---

## 🧠 Features

### 👥 User Roles:
- **Admin:** Manage users and books
- **Librarian:** Issue and return books
- **Student:** Search and request books

### 📦 Modules:
- User registration & login with Spring Security
- Add, edit, delete, and view books
- Search books by title, author, category
- Issue and return book functionality
- Track borrowed books per user
- Role-based access to routes and views

---

## 🖼️ Screenshots

> *(Include screenshots of the login page, dashboard, book list, and issue screen here if available)*

---

## 📂 Project Structure
src/
├── controller/
├── model/
├── repository/
├── service/
├── security/
├── templates/
└── application.properties
---

## ⚙️ How to Run

### ✅ Prerequisites

- Java 17+
- Maven
- MySQL Server
🔐 Default Users

Role          Username    Password

Admin          admin      admin123

Librarian    librarian     lib123

Student       student      stu123


✨ Acknowledgements
	•	Spring Boot Docs: https://spring.io/projects/spring-boot
	•	Thymeleaf Docs: https://www.thymeleaf.org
	•	Bootstrap: https://getbootstrap.com



