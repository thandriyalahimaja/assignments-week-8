# MERN Assignments – Week 8

## Project Overview
Purpose:

Learn REST API development
Connect React frontend with Express backend
Practice CRUD operations
Understand API calls using frontend
Learn routing in React
Understand backend server setup
Main Goal

To build a simple full-stack application where frontend and backend communicate with each other.

This project is a simple MERN stack application built using:

* **MongoDB** (optional / future integration)
* **Express.js**
* **React.js**
* **Node.js**
* **Vite** for frontend development

The application demonstrates basic user management functionality such as:

* Adding users
* Viewing all users
* Routing using React Router
* Backend API integration
* REST API development using Express

---

# Project Structure

```bash
MERN-assignments-week-8-main/
│
├── backend/
│   ├── apis/
│   ├── models/
│   ├── server.js
│   ├── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│
└── README.md
```

---

# Technologies Used

## Frontend

* React.js
* Vite
* React Router
* CSS

## Backend

* Node.js
* Express.js
* CORS
* Nodemon

---

# Features

## Frontend Features

* Home page
* User page
* Add User form
* User List page
* Navigation using React Router
* API calls to backend

## Backend Features

* REST API using Express
* GET users API
* POST user API
* In-memory data storage
* Error handling

---

# API Endpoints

## Get All Users

```http
GET /users
```

### Response

```json
{
  "message": "Users fetched successfully",
  "payload": []
}
```

---

## Add User

```http
POST /users
```

### Request Body

```json
{
  "name": "John",
  "email": "john@example.com"
}
```

### Response

```json
{
  "message": "User created successfully",
  "payload": {
    "_id": "123456",
    "name": "John",
    "email": "john@example.com"
  }
}
```

---

# Installation and Setup

## 1. Clone Repository

```bash
git clone <repository-url>
```

---

# Backend Setup

## Navigate to Backend Folder

```bash
cd backend
```

## Install Dependencies

```bash
npm install
```

## Start Backend Server

```bash
npm run dev
```

OR

```bash
npm start
```

Backend runs on:

```bash
http://localhost:3000
```

---

# Frontend Setup

## Navigate to Frontend Folder

```bash
cd frontend
```

## Install Dependencies

```bash
npm install
```

## Start Frontend

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# Available Scripts

## Backend

```bash
npm run dev
```

Runs backend using nodemon.

```bash
npm start
```

Runs backend using Node.js.

---

## Frontend

```bash
npm run dev
```

Starts Vite development server.

```bash
npm run build
```

Creates production build.

```bash
npm run preview
```

Previews production build.

---

# React Routes

| Route        | Description       |
| ------------ | ----------------- |
| `/`          | Home Page         |
| `/user`      | User Page         |
| `/userslist` | Display All Users |
| `/adduser`   | Add User Form     |

---

# Future Improvements

* MongoDB database integration
* User authentication
* Update/Delete user functionality
* Form validation
* Responsive UI improvements
* Redux or Context API state management

---

# Learning Outcomes

This project helps in understanding:

* MERN stack basics
* REST API development
* React routing
* Frontend-backend communication
* CRUD operations
* Express middleware
* Component-based architecture

---

