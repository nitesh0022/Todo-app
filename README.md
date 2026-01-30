# Todo-app
# Todo App

A full-stack **Todo application** built with **React**, **Node.js/Express**, **PostgreSQL**, and **Firebase Authentication**.  
Users can **sign up, login, create boards, add todos**, and manage them easily.

---

## Features

- **User Authentication**
  - Firebase email/password login
  - Firebase Google login
- **Boards**
  - Create, update, delete boards
  - Boards are user-specific
- **Todos**
  - Create, update, delete todos inside boards
  - Mark todos as pending or done
- **JWT Token**
  - Backend verifies JWT for secure APIs
- **Responsive UI**
  - Clean and simple interface

---

## Tech Stack

- **Frontend:** React, React Router, CSS  
- **Backend:** Node.js, Express, PostgreSQL  
- **Authentication:** Firebase Authentication  
- **Database:** PostgreSQL  
- **Others:** bcryptjs for password hashing, JWT for token authentication

---

## Folder Structure
todo-app/
│
├── backend/
│ ├── db.js # PostgreSQL connection & table creation
│ ├── server.js # Express server & API routes
│
├── frontend/
│ ├── src/
│ │ ├── App.js # React Router & main app
│ │ ├── Login.js # Login / Signup page
│ │ ├── Boards.js # Boards page
│ │ ├── Todos.js # Todos page
│ │ ├── api.js # API helper
│ │ └── App.css # Styles
│ └── public/
│ └── index.html
│
└── README.md


---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/<username>/todo-app.git
cd todo-app

2. Backend setup
cd backend
npm install


Create .env file in backend/:

DB_USER=<your_postgres_user>
DB_PASSWORD=<your_postgres_password>
DB_NAME=<your_database_name>
DB_HOST=localhost
JWT_SECRET=<your_jwt_secret>
PORT=5000


Start the server:

node server.js

3. Frontend setup
cd ../frontend
npm install
npm start


The frontend will run on http://localhost:3000/.
