# 📈 TradeX – Full Stack Stock Trading Platform 

TradeX is a full-stack web application that simulates an online stock trading platform like Zerodha. It enables users to register, log in, view stock charts, track portfolios, place buy/sell orders, and analyze their trading activities in a secure and real-time environment.

## 🚀 Features

- 🧑‍💼 **User Authentication** – Register, login, and logout with secure JWT-based auth
- 📊 **Live Stock Data** – Fetch and display real-time stock prices and charts
- 💼 **Portfolio Management** – Track holdings, watchlist, and transaction history
- 🛒 **Buy/Sell Orders** – Seamlessly place market or limit orders
- 📈 **Interactive Charts** – Candlestick and line charts powered by charting libraries
- 🔒 **Protected Routes** – Only logged-in users can access trading functionalities
- 📬 **Email Notifications** – Trade confirmation emails
- ⚙️ **Admin Panel** – Manage users, trades, and logs (optional feature)

## 🛠 Tech Stack

### 💻 Frontend
- React.js
- Tailwind CSS / CSS Modules
- Axios
- Chart.js or TradingView Widgets

### 🌐 Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT)
- bcrypt.js (password hashing)

### 🔧 Other Tools
- dotenv (environment variable handling)
- nodemailer (email notifications)
- CORS, Helmet, Morgan (security and logging middleware)

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/tradeX.git
cd tradeX
