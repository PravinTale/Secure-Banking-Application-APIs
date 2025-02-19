![ER diagram Secure Banking](https://github.com/user-attachments/assets/486fea9b-3deb-4ae4-9987-352a5f49d2f9)

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
# Key Features:

 # User Management: 
 Handles user registration, authentication, and profile management.
  # Account Management: 
  Manages user accounts, including creation, updating, and retrieval.
  # Card Services: 
  Provides functionalities for managing user cards.
  # Investment Management: 
  Manages user investments, allowing CRUD operations.
  # Nominee Management: 
  Manages nominee details associated with user accounts.
  # Exception Handling: 
  Centralized mechanism to handle application exceptions.
  # Security: 
  Implements JWT authentication and authorization using Spring Security.

---

## 🚀 Getting Started  

### 📥 Clone Repository  
```bash
git clone https://github.com/PravinTale/Secure-Banking-Application-APIs
cd Secure-Banking-Application-APIs

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

![ER diagram Secure Banking](https://github.com/user-attachments/assets/4ab13303-cce2-4888-9a33-c21a23cfd76c)

