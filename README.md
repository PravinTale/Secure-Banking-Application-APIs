# 🚀 Secure Banking Application API  

## 📌 Overview  
The **Secure Banking Application API** is a **Spring Boot-based** RESTful service designed for secure banking operations. It offers features like **user authentication, account management, fund transfers, and transaction history**, ensuring robust security through **JWT-based authentication** and **role-based access control**.  

---

## 🛠️ Tech Stack  
- **Spring Boot** (Java)  
- **Spring Security & JWT** 🔐  
- **Spring Data JPA** (Hibernate)  
- **PostgreSQL/MySQL** 🗄️  
- **Swagger API Documentation** 📄   

---

## 🎯 Features  
✅ **User Registration & Login (JWT Authentication)**  
✅ **Role-Based Access Control (Admin, User)**  
✅ **Secure Transactions with Input Validation**  
✅ **Encrypted User Data (BCrypt Encryption)**  
✅ **RESTful API Endpoints** for easy integration  
✅ **Exception Handling & Logging**  

---

## 🚀 Getting Started  

### 📥 Clone Repository  
```bash
git clone https://github.com/your-repo/banking-api.git
cd banking-api

⚙️ Configure Application
Update application.properties with your database credentials and JWT settings.

🏗️ Build & Run
mvn clean install  
mvn spring-boot:run

## 🔑 **Authentication Endpoints**  
Endpoints for **user authentication and JWT token generation**.  

| Method | Endpoint | Description |
|--------|---------|------------|
| `POST` | `/auth/register` | Register a new user |
| `POST` | `/auth/login` | Authenticate user and generate JWT token |
| `POST` | `/auth/logout` | Logout user and invalidate token |

### 📝 **Example Request - Register**  
```json
{
  "username": "john_doe",
  "password": "securePass123",
  "email": "john@example.com"
}
✅ Example Response

{
  "message": "User registered successfully!",
  "userId": 101
}  

