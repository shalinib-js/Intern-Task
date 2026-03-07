# 🛒 Product Management App (React + Backend)

A full-stack web application that allows users to browse products, view product details, and manage authentication. The project is built using React for the frontend and Node.js + Express with MongoDB for the backend.

---

## 📌 Features

- Login form with validation
- User login authentication
- User data stored in MongoDB
- Product listing
- Product search functionality
- Product filtering by category
- Product details view
- RESTful API integration
- Responsive UI built with React

---

## 🚀 Tech Stack

### Frontend
- React (Vite)
- JavaScript (ES6+)
- CSS
- Bootstrap

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

---
## 🗂️ Project Structure
<pre>
Intern-Task
│
├── Frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── Backend
│   ├── models
│   │   ├── User.js
│   │   └── product.js
│   │
│   ├── routes
│   │   ├── auth.js
│   │   └── productRoutes.js
│   │
│   ├── server.js
│   └── package.json
│
└── README.md
</pre>

## Project Architecture

### The application follows a client–server architecture:
<pre>
Frontend (React + Vite)
        ↓
REST API Requests
        ↓
Backend (Node.js + Express)
        ↓
Database (MongoDB)
</pre>

##  Screenshots
![Screenshot_7-3-2026_20353_localhost](https://github.com/user-attachments/assets/9792fe17-c894-4854-8a65-105fac8879b0)
![Screenshot_7-3-2026_20414_localhost](https://github.com/user-attachments/assets/ee7f47dc-f904-4cf3-b007-d4452305d0d9)
![Screenshot_7-3-2026_20528_localhost](https://github.com/user-attachments/assets/9869aace-5285-497e-a6fd-502669fe2e44)


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/intern-task.git
cd intern-task
```

---

### 2️⃣ Run Frontend (React)

```bash
cd Frontend
npm install
npm run dev
```

Frontend will run on:
`http://localhost:5173`

---

### 3️⃣ Run Backend (Node.js)

```bash
cd Backend
npm install
npm run start-dev
```

Backend server will run on:
`http://localhost:5000`



