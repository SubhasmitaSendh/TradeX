# 📈 TradeX - MERN Trading Platform

TradeX is a full-stack MERN-based trading platform that simulates an online stock trading experience. It allows users to securely register, verify their account using OTP, manage their portfolio, maintain a watchlist, and place buy/sell orders through an intuitive and responsive interface.

---

## 🚀 Features

* 🔐 Secure User Authentication (JWT + Bcrypt)
* 📧 Email OTP Verification
* 👤 User Registration & Login
* 📊 Interactive Trading Dashboard
* 📈 Stock Price Charts
* 💼 Portfolio Management
* ⭐ Watchlist Functionality
* 💰 Buy & Sell Order Management
* 🔍 Stock Search
* 📄 Automated PDF Generation
* 🛡️ Security using Helmet, CORS, and Express Middleware

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Router
* Axios
* Framer Motion
* Lightweight Charts
* Recharts

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt
* Nodemailer
* Express Validator
* Helmet
* CORS
* Morgan

---

## 📂 Project Structure

```
TradeX
│
├── client/          # React Frontend
├── server/          # Express Backend
├── routes/          # API Routes
├── models/          # MongoDB Models
├── controllers/     # Business Logic
├── middleware/      # Authentication & Validation
├── utils/           # Helper Functions
└── config/          # Configuration Files
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/TradeX.git
```

### 2. Navigate to the Project

```bash
cd TradeX
```

### 3. Install Dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd ../server
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the server directory and add the required configuration values such as:

* MongoDB URI
* JWT Secret
* Email Credentials
* Other environment-specific variables

### 5. Run the Application

Backend

```bash
npm run dev
```

Frontend

```bash
npm run dev
```

---

## 📌 Key Modules

* Authentication
* OTP Verification
* Trading Dashboard
* Portfolio
* Watchlist
* Buy/Sell Orders
* Stock Search
* Email Notifications
* PDF Reports

---

## 🎯 Learning Outcomes

This project helped strengthen practical knowledge of:

* Full-Stack MERN Development
* REST API Development
* MongoDB Database Design
* JWT Authentication
* Secure Password Hashing
* Email Integration
* State Management in React
* API Integration
* Responsive UI Development

---


## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is developed for learning and portfolio purposes.
