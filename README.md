
# 🛍️ Online Shopping Web App

![React](https://img.shields.io/badge/Frontend-React-blue)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

An e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js). This application allows users to browse products, manage their cart, and complete orders, with admin functionality for managing inventory and user data.

---

## ✨ Key Features

- 🔐 **User Authentication**: Registration, login, and JWT-based session handling.
- 🛍️ **Product Browsing**: Searchable and filterable product listings.
- 🛒 **Shopping Cart**: Add, update, and remove items.
- 📦 **Order Placement**: Seamless checkout and order summary.
- 🛠️ **Admin Panel**: Manage products, users, and orders.

---

## 🧰 Tech Stack

| Frontend   | Backend     | Database | Styling    | Others           |
|------------|-------------|----------|------------|------------------|
| React.js   | Node.js     | MongoDB  | Bootstrap  | Axios, Redux     |
| Redux      | Express.js  | Mongoose | CSS        | JWT, dotenv      |

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- [Node.js & npm](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- Git

---

### 📦 Installation Steps

1. **Clone the repository**

```bash
git clone https://github.com/nahida-athanikar/Online-Shopping-Web-App.git
cd Online-Shopping-Web-App
```

2. **Backend Setup**

```bash
cd backend
npm install
```

3. **Frontend Setup**

```bash
cd ../frontend
npm install
```

---

### ⚙️ Configuration

#### Backend `.env`

Create a `.env` file inside the `backend` directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

#### Frontend `.env`

Create a `.env` file inside the `frontend` directory and add:

```env
REACT_APP_API_URL=http://localhost:5000/api
```

---

### ▶️ Running the Application

#### Start Backend

```bash
cd backend
npm run dev
```

#### Start Frontend

```bash
cd ../frontend
npm run start
```

🖥️ Visit: [http://localhost:3000](http://localhost:3000)

---

## 🧪 How to Test

- Register or log in.
- Browse and search products.
- Add/remove items to/from cart.
- Checkout and view order summary.
- Admins can log in and manage inventory.

---

## 📂 Project Structure

```
Online-Shopping-Web-App/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── App.js
│   ├── .env
│   └── package.json
└── README.md
```

---

## 🙌 Contributing

We welcome contributions! Please fork the repo and open a pull request with your improvements.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🌐 Live Demo (Optional)

> _You can deploy this app on platforms like Vercel, Netlify (Frontend) and Render, Railway (Backend)._ 🚀

---

