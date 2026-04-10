# 💳 E-Banking System - Spring Boot REST API

## 📌 Project Overview

The **E-Banking System** is a backend application developed using **Spring Boot** that provides REST APIs for handling banking operations such as account management and transactions.

This project showcases strong backend development skills including REST API design, layered architecture, and database integration.

---

## 🚀 Features

* 👤 Create and manage bank accounts
* 💰 Deposit and withdraw money
* 🔄 Transfer funds between accounts
* 📄 View transaction history
* 🏗️ Clean layered architecture (Controller, Service, Repository)

---

## 🛠️ Tech Stack

* **Java**
* **Spring Boot**
* **MySQL**
* **Maven**
* **Postman (API Testing)**

---

## 📂 Project Structure

```id="a1b2c3"
src/
 ├── main/
 │   ├── java/
 │   │   ├── controller/
 │   │   ├── service/
 │   │   ├── repository/
 │   │   ├── model/
 │   ├── resources/
 │       ├── application.properties
pom.xml
```

---

## ⚙️ Setup Instructions

### 1️⃣ Download the Project

* Click **Code → Download ZIP** from GitHub
* Extract the ZIP file

---

### 2️⃣ Open in IDE

* Open the project in **Eclipse / IntelliJ / VS Code**

---

### 3️⃣ Configure Database

Update `application.properties`:

```id="d4e5f6"
spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_username
spring.datasource.password=your_password
```

---

### 4️⃣ Run the Application

* Run the main Spring Boot class
  **OR**

```id="g7h8i9"
mvn spring-boot:run
```

---

## 📡 API Endpoints

| Method | Endpoint               | Description         |
| ------ | ---------------------- | ------------------- |
| POST   | /api/accounts          | Create account      |
| GET    | /api/accounts/{id}     | Get account details |
| POST   | /api/accounts/deposit  | Deposit money       |
| POST   | /api/accounts/withdraw | Withdraw money      |
| POST   | /api/accounts/transfer | Transfer funds      |

---

## 🧪 Testing

Use **Postman** to test the APIs by sending HTTP requests.

---

## 📈 Future Enhancements

* Add JWT Authentication 🔐
* Build frontend (React / Angular) 🌐
* Deploy on cloud (AWS) ☁️

---

## 👩‍💻 Author

**Vandhana Thatikrindi**
Aspiring Java Full Stack Developer

---

## ⭐ Note

This project is created for learning and demonstrating backend development skills using Spring Boot.

---

