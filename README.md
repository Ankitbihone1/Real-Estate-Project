# 🏠 Real Estate Management System



A Full-Stack Real Estate Management System built using **Spring Boot, React.js, and MySQL**. This application enables users to browse properties, manage listings, submit inquiries, and perform secure online payments through Razorpay.



## 📌 Features



### 👤 User Management



* User Registration

* Profile Management

* User Information Update

* User Account Administration



### 🏡 Property Management



* Add New Property Listings

* Update Property Details

* Delete Properties

* View Available Properties

* Search and Filter Properties



### 📩 Inquiry Management



* Submit Property Inquiries

* Manage Customer Requests

* Track Property Enquiries



### 💳 Payment Integration



* Razorpay Payment Gateway Integration

* Secure Online Transactions

* Payment Status Tracking



### 📊 Admin Dashboard



* Manage Properties

* Manage Users

* View Customer Inquiries

* Monitor Transactions

* Property Listing Administration



## 🛠️ Technology Stack



### Frontend



* React.js

* Vite

* JavaScript

* HTML5

* CSS3

* Axios



### Backend



* Java 21

* Spring Boot

* Spring Data JPA

* Hibernate

* Maven



### Database



* MySQL



### Payment Gateway



* Razorpay





## 📂 Project Structure

```text
Real_Estate_Project
│
├── 📁 Estate_Managment_frontend
│   ├── 📁 src
│   ├── 📁 public
│   ├── 📄 package.json
│   └── 📄 vite.config.js
│
├── 📁 Real_Estate_Management
│   ├── 📁 src
│   ├── 📄 pom.xml
│   ├── 📄 mvnw
│   └── 📄 application.properties
│
├── 📄 README.md
└── 📄 .gitignore
```

## 🚀 Getting Started

### Prerequisites

Before running this project, ensure you have the following installed:

* Java 21 or later
* Maven
* Node.js
* npm
* MySQL
* Git

---

## ⚙️ Backend Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/Real-Estate-Management-System.git
```

### 2. Navigate to Backend Folder

```bash
cd Real_Estate_Management
```

### 3. Create Database

```sql
CREATE DATABASE real_estate_management;
```

### 4. Configure Database

Update the `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/real_estate_management
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 5. Run Backend

```bash
mvn spring-boot:run
```

Backend runs on:

```text
http://localhost:8080
```

---

## 💻 Frontend Setup

### 1. Navigate to Frontend Folder

```bash
cd Estate_Managment_frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## 🔗 API Modules

* User Management API
* Property Management API
* Inquiry Management API
* Payment Management API

---

## 🔒 Security Notes

Before pushing the project to GitHub:

* Remove database passwords
* Remove Razorpay Secret Keys
* Use environment variables for sensitive data
* Add `.env` files to `.gitignore`

---

## 🌟 Future Enhancements

* JWT Authentication
* Role-Based Access Control (RBAC)
* Email Notifications
* Advanced Property Filters
* Google Maps Integration
* Property Comparison Feature
* Recently Viewed Properties
* Property Recommendation System

---

## 📜 License

This project is developed for learning and portfolio purposes.


