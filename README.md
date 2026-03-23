# 🧩 MongoDB & Mongoose Integration API

###  User Management Service

A robust and scalable **User Database API** built with **Node.js**, **Express**, and **MongoDB** using **Mongoose ODM**.
This project demonstrates clean architecture and full CRUD functionality for managing user data.

---

## 🚀 Features

* 🔗 **Database Integration**
  Secure connection to MongoDB using Mongoose.

* 🧱 **Data Modeling**
  Structured user schema with validation and constraints.

* 🌐 **RESTful API Design**
  Clean, predictable endpoints for resource management.

* 🔐 **Environment Configuration**
  Sensitive data handled securely via `.env` variables.

* 🔄 **Full CRUD Operations**

  * **Create** → Register new users
  * **Read** → Retrieve all users or a specific user
  * **Update** → Modify existing user data
  * **Delete** → Remove users from the database

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* dotenv
* nodemon

---

## 📁 Project Structure

```
.
├── controllers/
│   └── userController.js
├── models/
│   └── User.js
├── routes/
│   └── userRoutes.js
├── .env
├── package.json
├── server.js
└── README.md
```

---

## ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/munawarkhan1206/mongodb-mongooese-crud-assignment.git
cd mongodb-mongooese-crud-assignment
```

### Install Dependencies

```bash
npm install
```

### Setup Environment Variables

Create a `.env` file and add:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### Run the Server

Development:

```bash
npm run dev
```

Production:

```bash
npm start
```

---

## 🔗 API Endpoints

* GET /users → Get all users
* GET /users/:id → Get user by ID
* POST /users → Create user
* PUT /users/:id → Update user
* DELETE /users/:id → Delete user

---

## 👤 Author

Munawar Khan
https://github.com/munawarkhan1206

---

## ⚠️ Notes

* Make sure MongoDB is running or Atlas IP is whitelisted
* Do NOT upload your `.env` file

---

## 🚀 Happy Coding!
