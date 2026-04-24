# 🛒 SmartCart – Full-Stack JavaScript E-Commerce App

SmartCart is a modern, scalable full-stack e-commerce web application built entirely with JavaScript. It provides a seamless shopping experience with secure authentication, dynamic product management, and real-time cart functionality.

---

## 🚀 Live Demo

🔗 *Coming Soon*

---

## 📌 Features

### 🧑‍💻 User Features

* User registration & login (JWT-based authentication)
* Browse products with search & filters
* Add to cart / remove from cart
* Secure checkout flow
* Order history tracking

### 🛠️ Admin Features

* Add / update / delete products
* Manage users
* View and process orders

### ⚡ Core Functionalities

* Responsive UI for all devices
* RESTful API architecture
* State management for cart
* Secure password hashing
* Error handling & validation

---

## 🏗️ Tech Stack

### Frontend

* React
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express

### Database

* MongoDB

### Authentication

* JSON Web Tokens (JWT)
* bcrypt.js

---

## 📁 Project Structure

```
smartcart/
│
├── client/          # Frontend (React)
│   ├── components/
│   ├── pages/
│   └── services/
│
├── server/          # Backend (Node.js + Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/smartcart.git
cd smartcart
```

---

### 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

Run backend:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

## 🔌 API Endpoints (Sample)

### Auth

* `POST /api/auth/register`
* `POST /api/auth/login`

### Products

* `GET /api/products`
* `POST /api/products` (Admin)

### Cart

* `POST /api/cart`
* `GET /api/cart`

### Orders

* `POST /api/orders`
* `GET /api/orders`

---

## 🧠 Future Improvements

* 💳 Payment Integration (Stripe / Razorpay)
* 📦 Order tracking system
* ⭐ Product reviews & ratings
* 🔍 AI-based product recommendations
* 📊 Admin analytics dashboard

---

## 🛡️ Security

* Password hashing with bcrypt
* JWT-based authentication
* Protected API routes
* Input validation & sanitization

---

## 📸 Screenshots

*Add screenshots here*

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* OpenAI (for AI inspiration)
* Open-source community

---

## 💼 Resume Description

> Developed a full-stack e-commerce platform using React, Node.js, Express, and MongoDB with secure authentication, dynamic cart management, and RESTful APIs supporting scalable online transactions.

---
