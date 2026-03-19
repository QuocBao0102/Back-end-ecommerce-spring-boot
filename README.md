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

👉 Đây là stack rất phổ biến trong các project e-commerce backend thực tế ([GitHub][1])

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

## 🔑 API Overview

| Method | Endpoint       | Description      |
| ------ | -------------- | ---------------- |
| POST   | /auth/login    | Login user       |
| POST   | /auth/register | Register user    |
| GET    | /products      | Get all products |
| POST   | /products      | Create product   |
| PUT    | /products/{id} | Update product   |
| DELETE | /products/{id} | Delete product   |
| POST   | /cart          | Add to cart      |
| POST   | /orders        | Place order      |

---

## 📸 Demo (Optional)

> Bạn có thể thêm ảnh Swagger / Postman ở đây

---

## 🧠 Future Improvements

* ✅ Payment integration (VNPay / Stripe)
* ✅ Docker deployment
* ✅ Unit & Integration testing
* ✅ Caching (Redis)
* ✅ Microservices architecture

---

## 👨‍💻 Author

* **Quoc Bao Ho**
* GitHub: https://github.com/QuocBao0102

---

## ⭐ If you find this project helpful

Give it a ⭐ on GitHub!

[1]: https://github.com/mdasharaf07/Springboot-ecommerce?utm_source=chatgpt.com "GitHub - mdasharaf07/Springboot-ecommerce: A Spring Boot e-commerce project demonstrates how to build a real-world web application with features like authentication, product management, and order processing."
