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

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ee14fa12-87e2-4dd9-82e9-d58875cd4da5" />

