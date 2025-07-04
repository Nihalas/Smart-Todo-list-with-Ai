# Smart-Todo-list-with-Ai
# 🧠 Smart Todo List App

An intelligent task management application that uses AI to suggest deadlines, priorities, and categorization based on your daily context like emails, WhatsApp messages, and notes.

## 🚀 Tech Stack

- **Frontend:** Next.js + Tailwind CSS
- **Backend:** Django REST Framework
- **Database:** PostgreSQL (Supabase)
- **AI:** OpenAI API / Claude API / LM Studio (local)

---

## 📦 Folder Structure

| Folder     | Description                             |
|------------|-----------------------------------------|
| `backend/` | Django backend APIs + AI logic          |
| `frontend/`| Next.js frontend with Tailwind styling  |

---

## 🛠 Setup Instructions

### Backend Setup (Django)

```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
python manage.py migrate
python manage.py runserver
