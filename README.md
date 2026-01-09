
#  Library Management System

##  Project Title

**Library Management System**



##  Project Description

The **Library Management System** is a web-based application designed to simplify and automate daily library operations. It provides an efficient way to manage books, users, and borrowing activities while ensuring secure role-based access.

The system helps students easily browse and borrow books, while allowing the library in-charge (admin) to manage inventory and track book availability. It is built using the **MERN stack**, following modern development practices.

**Target Users:**

* Students
* Library In-Charge (Admin)



##  Features

### Student Features

* User registration and secure login
* Browse and view available books
* Borrow and return books
* View borrowed books history

### Admin Features

* Add, update, and delete books
* Track borrowed books and borrowers
* Monitor real-time book availability

### System Features

* Role-based access control (Student/Admin)
* Secure authentication using JWT
* Password encryption with bcrypt


##  Technology Stack

### Frontend

* React.js

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose ODM

### Authentication & Security

* JSON Web Tokens (JWT)
* bcrypt for password hashing


##  System Roles

### Student

* Browse books
* Borrow and return books
* View borrowing history

### Admin (Library In-Charge)

* Manage book records
* Track borrowers
* Monitor inventory and availability



##  Project Structure

```
library-management-system/
│
├── client/        # React frontend
├── server/        # Node + Express backend
├── models/        # MongoDB schemas
├── routes/        # API routes
├── controllers/   # Business logic
├── config/        # Database & environment configuration
└── README.md
```



##  Installation & Setup

### Prerequisites

* Node.js
* MongoDB

### Steps

1. Clone the repository

   ```bash
   git clone <repository-url>
   ```
2. Install backend dependencies

   ```bash
   cd server
   npm install
   ```
3. Install frontend dependencies

   ```bash
   cd client
   npm install
   ```
4. Configure environment variables
5. Start backend and frontend servers


##  Environment Variables

Create a `.env` file in the server directory and configure:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```



##  API Endpoints (Optional)

* User authentication APIs
* Book management APIs
* Borrow and return book APIs

*All APIs follow REST standards and return JSON responses.*



## 🗄 Database Schema Overview

* **Users Collection**
  Stores student and admin user details

* **Books Collection**
  Stores book information and availability

* **Borrow Records Collection**
  Tracks borrowing and return history



##  Future Enhancements

* Due date reminders
* Fine calculation for late returns
* Book search and filtering
* Admin analytics dashboard



##  Conclusion

The Library Management System provides an organized, secure, and user-friendly solution for managing library operations. This project helped in understanding full-stack development, authentication, database design, and role-based access control using the MERN stack.



##  Author / Contributors

**Marakala Sowmya**




* Add **API documentation**
* Convert this into a **college project report**
* Customize it for **GitHub with badges & screenshots**

Just tell me 😄
