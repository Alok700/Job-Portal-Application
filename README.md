# Job Portal Application (MERN Stack)

A full-stack **Job Portal web application** built using the **MERN stack** that allows users to search and apply for jobs, and recruiters to post and manage job listings.

---

## 🚀 Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS
- Redux Toolkit
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

## ✨ Features

### 👤 User
- User registration & login
- Browse and search jobs
- Filter jobs by category
- Apply for jobs
- Secure authentication

### 🧑‍💼 Recruiter
- Recruiter login
- Post new jobs
- Manage job listings
- View applicants

### ⚙️ General
- RESTful APIs
- Redux state management
- Responsive UI
- Secure environment variables

---

## 📁 Project Structure

JOB PORTAL/
│
├── backend/
│ ├── JS/
│ ├── index.js
│ ├── package.json
│ ├── package-lock.json
│ └── .env (ignored)
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ ├── hooks/
│ │ ├── lib/
│ │ ├── redux/
│ │ └── utils/
│ ├── App.jsx
│ ├── main.jsx
│ ├── index.css
│ ├── App.css
│ ├── tailwind.config.js
│ ├── postcss.config.js
│ ├── vite.config.js
│ ├── package.json
│ └── package-lock.json
│
├── .gitignore
├── OUTLINE
├── TIMELINE
└── README.md

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Job-Portal.git
cd Job-Portal

2️⃣ Backend Setup
cd backend
npm install
npm run dev

Create a .env file inside the backend folder:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev
