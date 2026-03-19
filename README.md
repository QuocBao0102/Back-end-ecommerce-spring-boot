# 🛒 E-Commerce Backend API (Spring Boot)

## 📌 Introduction

This project is a **RESTful backend system for an E-commerce application** built with Spring Boot.
It provides core functionalities such as **user authentication, product management, shopping cart, and order processing**.

The system is designed following a clean architecture approach, making it scalable and easy to integrate with any frontend (Web, Mobile).

---

## 🚀 Features

* 🔐 Authentication & Authorization (JWT)
* 👤 User Management (Register / Login)
* 📦 Product Management (CRUD)
* 🗂 Category Management
* 🛒 Shopping Cart
* 📑 Order Processing
* 🔍 Search & Filter products
* 📊 Pagination API

---

## 🛠 Tech Stack

* **Backend:** Spring Boot, Spring Web
* **Security:** Spring Security, JWT
* **Database:** MySQL
* **ORM:** Hibernate, Spring Data JPA
* **Build Tool:** Maven
* **API Testing:** Postman


---

## 🏗 Project Structure

```
src/main/java/com/yourproject/
│── controller      # REST API endpoints
│── service         # Business logic
│── repository      # Data access layer (JPA)
│── entity          # Database entities
│── dto             # Data transfer objects
│── config          # Security & config
│── exception       # Custom exception handling
```

---

## ⚙️ Installation & Run

### 1. Clone project

```bash
git clone https://github.com/QuocBao0102/Back-end-ecommerce-spring-boot.git
cd Back-end-ecommerce-spring-boot
```

### 2. Configure database

Update file `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password
```

### 3. Run application

```bash
mvn spring-boot:run
```

👉 Server will run at: `http://localhost:8080`

---



## 👨‍💻 Author

* **Quoc Bao Ho**
* GitHub: https://github.com/QuocBao0102

---



