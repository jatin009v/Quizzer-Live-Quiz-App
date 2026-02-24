🚀 Quizzer: Live Quiz App

🔗 Live Demo: https://quizzer-hazel-sigma.vercel.app/

💻 GitHub Repository: https://github.com/jatin009v/Quizzer-Live-Quiz-App

📌 About The Project

Quizzer is a full-stack real-time quiz hosting platform designed and developed by me ([Jatin Gupta](https://linkedin.com/in/jatingupta09)) as an open-source initiative for my college coding club.

This project was built under Code Vidya – Coding Club, Aatmoday, CSJMU Kanpur to enable seamless online quiz and exam hosting.

🔗 Code Vidya LinkedIn:
https://in.linkedin.com/company/codevidya-aatmoday

The goal of this project is to allow anyone to host live quizzes, exams, or competitions without technical difficulty.
It is designed to be simple, scalable, and accessible for students and organizations.

This project is fully open-source so that others can improve, customize, and use it freely.

🎯 This platform was conceptualized, architected, and implemented entirely by me to support real-time quiz events within Code Vidya and beyond.

------------------------------------------------------------------------


## ✨ Features

### 🎯 Core Functionality

-   Real-time question & answer updates
-   Multiple Question Types (MCQ + Text)
-   Timed Questions
-   Dynamic Scoring System
-   Live Leaderboard
-   Admin Control Panel

### 👨‍🎓 Player Features

-   Simple Registration (Name + Email)
-   Lifelines (50:50, Hints)
-   Answer Locking System
-   Real-time Score Tracking

### 🛠 Host Features

-   Upload & Manage Question Sets
-   Start / Pause / Resume / Reset Quiz
-   Reveal Answers with Stats
-   Sudden Death Mode
-   Player Monitoring
-   Custom Branding Support

### ⚙ Technical Features

-   JSON-based Data Storage
-   CORS Enabled
-   WebSocket Communication (Socket.IO)
-   Mobile Responsive UI
-   Clean & Modern UI using Tailwind CSS

------------------------------------------------------------------------

## 🛠 Tech Stack

### Frontend

-   React
-   Vite
-   Tailwind CSS
-   TypeScript

### Backend

-   FastAPI
-   Python
-   Socket.IO

------------------------------------------------------------------------

## 🌍 Deployment

-   **Frontend:** Deployed on Vercel\
-   **Backend:** Hosted on AlwaysData\
-   Real-time communication powered by WebSockets

------------------------------------------------------------------------

## ⚙️ Setup Instructions

### Requirements

-   Node.js (v16+)
-   Python (v3.9+)

------------------------------------------------------------------------

### Backend Setup

``` bash
python -m venv .venv
.venv\Scripts\activate   # Windows
pip install -r backend/requirements.txt
uvicorn backend.app.main:asgi_app --reload
```

------------------------------------------------------------------------

### Frontend Setup

``` bash
cd frontend
npm install
npm run dev
```

For production:

``` bash
npm run build
```

------------------------------------------------------------------------

## 📍 Local Access URLs

-   Lobby → http://localhost:5173/
-   Admin → http://localhost:5173/admin
-   Display Screen → http://localhost:5173/display
-   API → http://localhost:8000/api

------------------------------------------------------------------------

## 🌱 Future Improvements

-   Database integration (PostgreSQL / MongoDB)
-   Advanced authentication system
-   Team mode
-   Media-based questions
-   Analytics dashboard
-   Multi-language support
-   Advanced UI themes

------------------------------------------------------------------------

## 👨‍💻 Author

**Jatin Gupta**\
MCA Student \| Full Stack Developer \| Open Source Contributor

🔗 GitHub: https://github.com/jatin009v\
🔗 LinkedIn: https://linkedin.com/in/jatingupta09\
🌐 Portfolio: https://jatinguptaportfolio.netlify.app

------------------------------------------------------------------------

## 🤝 Open Source Contribution

This project is open-source and built for **Code Vidya -- Coding Club,
Aatmoday, CSJMU Kanpur**.

Anyone can: - Use it to host quizzes or exams - Improve features -
Customize UI - Add new functionality - Contribute via Pull Requests

If you like this project, please ⭐ star the repository and support
open-source learning!

------------------------------------------------------------------------

## 📜 License

This project is licensed under the MIT License.

------------------------------------------------------------------------
