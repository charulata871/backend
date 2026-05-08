# 🌾 Krishi Wise Loan - Backend

Backend API for Krishi Wise Loan application built with Node.js, Express, and MongoDB.

---

## 🚀 Features
- User Registration & Login (JWT Auth)
- Loan EMI Analysis API
- Government Schemes API
- Weather API integration
- User history tracking
- MongoDB database integration

---

## 🛠 Tech Stack
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- bcryptjs
- Axios

---

## 📦 Installation

```bash
cd backend
npm install
⚙️ Environment Variables

Create .env file:

MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_secret_key
▶️ Run Server
node server.js

OR (if nodemon is installed):

npm run dev
🔗 API Routes
Auth
POST /api/register
POST /api/login
Loan Analysis
POST /api/analyze
Schemes
POST /api/schemes
History
GET /api/history/:name
Weather
GET /api/weather
