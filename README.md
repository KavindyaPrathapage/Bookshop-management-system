# 📚 Bookshop Management System

A full-stack application built to manage bookshop operations with a custom authentication system and a user-friendly interface.

---

## 🚀 Features

- 🔐 **Custom Authentication System** – Secure login/logout with session management  
- 📧 **Email Validation** – Gmail format verification for user registration  
- 📞 **Phone Validation** – International phone number validation using country code API  
- 👥 **User Management** – Manage customers and system users with proper access controls  
- 📦 **Inventory Management** – Complete item and stock management system  
- 🧾 **Billing & Invoicing** – Generate invoices and manage transactions  
- ❓ **Help & Support** – Integrated support module for users  

---

## 🛠 Tech Stack

- **Backend:** Spring Boot, Java, REST APIs  
- **Authentication:** Custom session-based authentication  
- **Validation:** Email format validation, Phone number validation via country code API  
- **Database:** MySQL (automatic table creation via Hibernate/JPA)  
- **Frontend:** HTML, CSS, JavaScript  
- **Build Tool:** Maven  

---

## 🗃️ Database Schema

- **user_model** – System users with authentication details  
- **customer_model** – Customer information with validated contact details  
- **item_model** – Product inventory with pricing  
- **purchase_model** – Transaction records and billing information  

> ⚡ Note: All tables are **automatically created by Hibernate/JPA** based on entity classes when the application starts. No need to manually import SQL schema.

---

## 🔧 Setup & Installation

### 1. Clone the repository
bash
git clone https://github.com/your-username/bookshop-management-system.git
cd bookshop-management-system

### 2. Database Setup

Install MySQL and create database:

sql
CREATE DATABASE my_database;
### 3.Configure Application

Update backend/src/main/resources/application.properties with your MySQL credentials

### 4.Run the Application

bash
cd backend
mvn spring-boot:run
### 5.Access the Application

Open browser and navigate to: http://localhost:8083

---

##🌐 API Endpoints
-**POST /api/login** - User authentication
-**POST /api/register** - User registration with email/phone validation
-**GET /api/customers** - Retrieve customer data
-**POST /api/items** - Add new inventory items
-**POST /api/purchases** - Create new transactions

---

##📸 Demo Video
**https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg**

---

##🚦 Validation Features

-**Email Validation: **Ensures proper Gmail/email format**
-**Phone Validation: **Uses country code API to validate international numbers
-**Input Sanitization: **Prevents SQL injection and XSS attacks
-**Session Management: **Secure user session handling

---

##📦 Dependencies

-**Spring Boot Web**
-**Spring Data JPA**
-**MySQL Connector**
-**ModelMapper**
-**Lombok**
-**Validation API**

---

##👨‍💻 Development

-**Backend: **Spring Boot 3.5.3
-**Java Version: **18
-**Database: **MySQL 8.0+
-**Frontend: **Vanilla JS with modern CSS

---

##📝 License

-**This project is licensed under the MIT License - see the LICENSE file for details.**

---

##🤝 Contributing

-**Fork the project**
-**Create your feature branch (git checkout -b feature/AmazingFeature)**
-**Commit your changes (git commit -m 'Add some AmazingFeature')**
-**Push to the branch (git push origin feature/AmazingFeature)**
-**Open a Pull Request**
