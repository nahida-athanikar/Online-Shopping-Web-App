
# 🛒 Online Shopping Web App

An online shopping platform that allows users to browse products, add items to their cart, and proceed to checkout. This project is structured with separate frontend and backend directories, facilitating modular development and deployment.

## 📌 Features

- **User Authentication:** Secure login and registration system.
- **Product Catalog:** Browse a variety of products with detailed descriptions.
- **Shopping Cart:** Add, remove, and update items in the cart.
- **Order Management:** Place orders and view order history.
- **Admin Panel:** Manage products, categories, and user orders.

## 🛠️ Technologies Used

### Frontend

- **React.js:** For building dynamic user interfaces.
- **Redux:** State management across the application.
- **Axios:** Handling HTTP requests.
- **Bootstrap:** Responsive design and styling.

### Backend

- **Node.js & Express.js:** Server-side development and API creation.
- **MongoDB:** NoSQL database for storing user and product data.
- **Mongoose:** Object Data Modeling (ODM) library for MongoDB.
- **JWT (JSON Web Tokens):** Authentication and authorization.

## 🚀 Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

Ensure you have the following installed:

- **Node.js:** [Download and install Node.js](https://nodejs.org/)
- **MongoDB:** [Download and install MongoDB](https://www.mongodb.com/try/download/community)
- **npm:** Comes with Node.js

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nahida-athanikar/Online-Shopping-Web-App.git
   cd Online-Shopping-Web-App
   ```

2. **Set up the backend:**

   ```bash
   cd backend
   npm install
   ```

3. **Set up the frontend:**

   ```bash
   cd ../frontend
   npm install
   ```

### Configuration

1. **Backend Configuration:**

   - Create a `.env` file in the `backend` directory.
   - Add the following environment variables:

     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```

2. **Frontend Configuration:**

   - Create a `.env` file in the `frontend` directory.
   - Add the following environment variable:

     ```env
     REACT_APP_API_URL=http://localhost:5000/api
     ```

### Running the Application

1. **Start the backend server:**

   ```bash
   cd backend
   npm run dev
   ```

2. **Start the frontend development server:**

   ```bash
   cd ../frontend
   npm run start
   ```

3. **Access the application:**

   - Open your browser and navigate to `http://localhost:3000`

## 🧪 Testing

- Ensure both frontend and backend servers are running.
- Register a new user or log in with existing credentials.
- Browse products, add items to the cart, and proceed to checkout.
- Access the admin panel to manage products and orders.

## 📁 Project Structure

```plaintext
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

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 📜 License

This project is licensed under the [MIT License](LICENSE).
