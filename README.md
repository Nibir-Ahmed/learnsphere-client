# LearnSphere – Online Learning Platform

🌐 **Live Site:** [https://learnsphere.netlify.app](https://learnsphere.netlify.app)

LearnSphere is a modern full-stack online learning platform where instructors can publish courses and learners can explore, enroll, and manage their learning journey — all in one place.

---

## ✨ Key Features

- 🔐 **Secure Authentication** — Email/password and Google login with Firebase, protected private routes, and password validation (uppercase, lowercase, min 6 chars).
- 📚 **Full Course Management** — Instructors can add, edit, and delete their own courses with real-time updates from MongoDB.
- 🎯 **Smart Course Filtering** — Browse all courses with live search and category-based filtering to find exactly what you need.
- 📊 **Personal Dashboard** — Dedicated dashboard to manage added courses and track enrolled courses in one place.
- 🎨 **Polished Animations** — Smooth Framer Motion animations on the homepage hero, course cards, and section reveals for a premium feel.

---

## 🛠 Tech Stack

**Frontend:** React, Vite, Tailwind CSS, Framer Motion, TanStack Query, Axios, React Router v6, Firebase Auth, React Hot Toast, SweetAlert2

**Backend:** Node.js, Express.js, MongoDB (Atlas), CORS, dotenv

**Hosting:** Netlify (client) · Vercel (server)

---

## 🚀 Getting Started

### Client

```bash
cd client
cp .env.example .env   # fill in your Firebase & server URL
npm install
npm run dev
```

### Server

```bash
cd server
cp .env.example .env   # fill in MongoDB credentials
npm install
npm run dev
```

---

## 📁 Project Structure

```
learning-platform/
├── client/          # React frontend
│   └── src/
│       ├── components/   # Navbar, Footer, CourseCard, ...
│       ├── contexts/     # AuthContext
│       ├── pages/        # Home, Login, Register, AllCourses, ...
│       │   └── Dashboard/
│       └── firebase/     # Firebase config
└── server/          # Express backend
    └── index.js
```
