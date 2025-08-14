💰 Expense Tracker (MERN)

A simple and responsive MERN stack web app to track income & expenses, view charts, and manage budgets.

🚀 Features

JWT-based user authentication

Add, view & delete income/expenses

Dashboard with totals & recent transactions

Charts for income/expenses (Recharts)

Profile image upload

Export data to Excel

Responsive UI (React + TailwindCSS)

🛠️ Tech Stack

Frontend: React (Vite), TailwindCSS, Axios, Recharts

Backend: Node.js, Express, MongoDB, Mongoose, Multer, JWT, bcrypt

Other: XLSX, dotenv

⚙️ Setup
# Clone repo
git clone <repo-url> && cd Expense-Tracker

# Backend
cd backend
npm install
# Create .env file
MONGO_URI=<mongodb-uri>
PORT=8000
CLIENT_URL=http://localhost:5173
JWT_SECRET=<secret>
npm run dev

# Frontend
cd ../frontend
npm install
npm run dev

📡 Main API Routes

Auth: /auth/register, /auth/login, /auth/getUser
Income: /income/add, /income/get, /income/:id
Expense: /expense/add, /expense/get, /expense/:id
Dashboard: /dashboard
