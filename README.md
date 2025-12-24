📊 Sentiment Intelligence Platform
A real-time dashboard that visualizes social media sentiment trends using FastAPI, React, PostgreSQL, and WebSockets. This platform analyzes incoming posts and provides live updates on sentiment distribution and cumulative growth trends.

🚀 Key Features
Real-time Dashboard: Live-updating charts and feeds using WebSockets.

Sentiment Distribution: Pie chart visualization of overall sentiment (Positive, Negative, Neutral).

Growth Trends: Cumulative line charts tracking sentiment activity over time.

Broadcasting System: An internal API endpoint for workers to push data to all connected clients.

Stat Summary: Quick-glance counters for total posts and sentiment categories.

🛠️ Tech Stack
Backend: FastAPI (Python), SQLAlchemy (Async), Uvicorn.

Frontend: React (Vite), Chart.js, React-Chartjs-2.

Database: PostgreSQL.

Containerization: Docker & Docker Compose.

🚦 Getting Started
1. Prerequisites
Docker & Docker Compose installed.

Python 3.10+ (for local testing).

2. Launch the Platform
From the root directory, run:

Bash

docker compose up --build
The services will be available at:

Frontend: http://localhost:3000 

Backend API: http://localhost:8000
