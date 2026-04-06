# DaySavvy (For Public)
**The Emotionally Intelligent AI Assistant**

DaySavvy is an AI-powered productivity companion that goes beyond task management. It's the first assistant that truly understands how you feel — offering personalized support, intelligent scheduling, and genuine emotional connection.

## 🚀 What Makes Us Different

- **Emotional Intelligence (EI)** — Our AI doesn't just manage tasks; it understands context, stress levels, and adapts its responses to support you
- **Action Extractor** — Snap a photo of your syllabus, whiteboard, or notes, and watch tasks automatically appear
- **Voice-First Experience** — Speak naturally to add tasks, check schedules, or chat with EI
- **Smart Reminders** — Get reminded at the right time, in the right way

## ✨ Key Features

### 🧠 Empathetic Intelligence (EI)
- Natural conversations that feel like talking to a caring friend
- Contextual awareness — remembers your preferences and history
- Stress detection and adaptive responses

### 📸 Action Extractor (Magic Feature)
- Upload photos of syllabi, handwritten notes, whiteboards
- AI automatically extracts tasks, deadlines, and action items
- Select or deselect individual tasks before adding them
- Auto-set priorities and due dates

### 🎤 Voice Commands
- Add tasks by speaking naturally
- Check your schedule hands-free
- Works on mobile and desktop

### 📧 Premium Auto-Task Execution
- Premium users can ask DaySavvy to draft emails directly from chat
- Example: "Draft an email to hr@company.com subject: Leave request body: I need leave tomorrow"
- DaySavvy returns an "Open Gmail Draft" link with recipient, subject, and body pre-filled
- If user asks "send", DaySavvy still opens a ready draft and Gmail requires the final Send click for security

### 📋 Smart Task Management
- Quick add, edit, complete, delete with instant feedback
- Automatic priority classification (Urgent/High/Normal/Low)
- Category badges (Work, Personal, Study, Other)
- Due dates with smart time suggestions

### 🔔 Intelligent Reminders
- Push notifications at the perfect time
- PWA support — works offline like a native app
- Personalized engagement messages

### 📅 Beautiful Calendar
- Visual task planning with drag-and-drop
- Week and month views
- Seamless integration with your task list

## 🛠️ Tech Stack

- **Backend:** Python 3.11+, Flask, SQLAlchemy
- **Frontend:** Jinja2, Bootstrap 5, Progressive Web App (PWA)
- **AI:** Groq Compound Beta (LLM), Vision AI for Action Extractor
- **Database:** SQLite (default), PostgreSQL-ready
- **Notifications:** Web Push (VAPID)

## 🏗️ Project Structure

```
DAYSAVVY/
├─ app.py              # Main Flask application
├─ templates/          # Jinja2 HTML templates
│  ├─ index.html       # Main dashboard
│  ├─ home.html        # Landing page
│  └─ ...
├─ static/             # CSS, JS, images
├─ models/             # Database models
├─ migrations/         # Database migrations
└─ README.md
```

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables (see `.env.example`)
4. Run: `python app.py`
5. Visit: `http://localhost:5000`

### Premium Gmail Automation Config

Set premium users by email in environment:

`PREMIUM_USER_EMAILS=user1@gmail.com,user2@gmail.com`

Only these users (or users with a future `is_premium` DB flag) can use Gmail draft automation from chat.

## 🌐 Live Demo

Try DaySavvy now at **[daysavvy.com](https://daysavvy.com)**

## 📬 Contact

- **Website:** [daysavvy.com](https://daysavvy.com)
- **Instagram:** [@daysavvy](https://instagram.com/daysavvy)
- **Twitter:** [@4rham_malik](https://x.com/4rham_malik)
- **Creator:** [Arham Malik](https://arhammalik.me)

---

Made with ❤️ by Arham Malik | © 2026 DaySavvy



