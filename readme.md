# 📋 Task Tracker with Smart Insights

A simple task management app with AI-powered insights. Track your to-dos, priorities, and deadlines in one place.

## ✨ Features

- ✅ Create and manage tasks with priorities and due dates
- 🔍 Filter by status and priority
- 💡 Smart workload insights and statistics
- ⚠️ Track overdue and upcoming tasks

## 🛠️ Tech Stack

**Backend:** Python, FastAPI, SQLite  
**Frontend:** React, CSS

## 🚀 Quick Start

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```
Runs at `http://localhost:8000`

### Frontend
```bash
cd frontend
npm install
npm start
```
Runs at `http://localhost:3000`

## 📂 Project Structure

```
bhavi/
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── requirements.txt
│   └── tasks.db
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── App.js
    │   └── App.css
    └── package.json
```

## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | Health check |
| POST | `/tasks` | Create task |
| GET | `/tasks` | Get all tasks (with filters) |
| PATCH | `/tasks/:id` | Update task |
| GET | `/insights` | Get analytics |

## 🎨 Key Features

**Smart Insights:** Workload summaries, status/priority breakdowns, overdue alerts

**Filters:** By status (todo, in_progress, done) and priority (Low, Medium, High)

**Task Properties:** Title, description, priority, status, due date

## 🛑 Stop Servers

Press `Ctrl + C` in both terminals

## 📄 License

Free for personal and learning use

---

Built as a full-stack demo project