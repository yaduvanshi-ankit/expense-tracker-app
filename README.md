# Expense Tracker — MERN Stack

This project is a MERN expense tracker: a React + Vite frontend, Node.js + Express API, and MongoDB through Mongoose. The React UI preserves the original Tailwind design and features, including expense management, AI quick-fill/insights, authentication, CSV export, and admin views.

## Project layout

```text
expense-tracker-app/
├── src/                 # React frontend
├── public/              # Static assets
├── backend/             # Express + MongoDB API
└── package.json         # React/Vite scripts
```

## Run locally

In one terminal, start the API (configure `backend/.env` first):

```bash
cd backend
npm install
npm start
```

In another terminal, start React:

```bash
npm install
npm run dev
```

The React app runs on `http://localhost:5173` and calls `http://localhost:5000/api` by default. Set `VITE_API_URL` to use a different API URL. Set `CLIENT_URL` in the backend environment for password-reset email links (for example, `http://localhost:5173`).

For social sign-in, set `CLIENT_URL=http://localhost:5173` and `BACKEND_URL=http://localhost:5000` in `backend/.env`. In the provider consoles, register these exact callback URLs:

- Google: `http://localhost:5000/api/auth/google/callback`
- GitHub: `http://localhost:5000/api/auth/github/callback`

## Stack

- MongoDB + Mongoose
- Express + Node.js
- React 19 + React Router + Vite
- Tailwind CSS + Font Awesome

- # Expense Tracker

## Live Demo
Live Link - https://expense-tracker-mr2pqnozy-ankit-yadavs-projects-4b006872.vercel.app/

Frontend:
https://your-vercel-url.vercel.app

Backend API:
https://expense-tracker-app-csdo.onrender.com

Swagger:
https://expense-tracker-app-csdo.onrender.com/api-docs

🏠 Home Page :
<img width="909" height="437" alt="image" src="https://github.com/user-attachments/assets/97cf4fa5-172d-4168-933b-16d86a0a8402" />


🔐 Login Page:
<img width="907" height="436" alt="image" src="https://github.com/user-attachments/assets/a9305a04-be39-43c5-9ef1-d332c402f3a6" />



📝 Signup Page:
<img width="908" height="434" alt="image" src="https://github.com/user-attachments/assets/b5f2eecc-b669-455b-8867-e7d89be2a0b6" />



💰 Dashboard:

<img width="894" height="420" alt="image" src="https://github.com/user-attachments/assets/a09bdee4-3f03-4102-910b-44c8bebc81e5" />



🤖 AI Expense Parser:

<img width="911" height="434" alt="image" src="https://github.com/user-attachments/assets/00cfb600-62c3-4f1b-8a64-f9604ed702ae" />




📊 Insights:

<img width="908" height="434" alt="image" src="https://github.com/user-attachments/assets/85e7df0f-3e7e-47a9-90bd-8c03f7e8a81d" />




