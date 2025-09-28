# StudySync - Group Study Scheduler

<img width="1536" height="1024" alt="ChatGPT Image Sep 29, 2025, 03_01_05 AM" src="https://github.com/user-attachments/assets/2ea93a7f-e9f8-49a9-87aa-a0d12e760fb3" />


## 📌 Overview

**StudySync** is a collaborative **Group Study Scheduler** designed to help students and teams plan, manage, and track study sessions effectively.  
It simplifies scheduling by allowing users to:
- Create study groups
- Schedule study sessions
- Send reminders and notifications
- Track attendance and progress
- Get analytics on study hours and participation

Whether you are preparing for exams, coding competitions, or collaborative projects, **StudySync** keeps everyone on the same page.

---

## 🏗 Project Architecture

The architecture follows a **modular and lightweight design** to ensure scalability and extensibility.  
Key components:
- **Core Components** – Session Management, Notification Engine, and Storage
- **API & UI/CLI** – Simple request/response flow for session creation and updates
- **Extensibility** – Add new integrations (e.g., Google Calendar, Slack notifications)
- **Deployment** – Can be run locally or in Docker

Refer to the diagram above for a detailed view of the system design.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/studysync.git
cd studysync
```

### Use the Repo
```bash
pip install -r requirements.txt
python main.py
docker build -t studysync .
docker run -p 8000:8000 studysync
```


## ⭐ Support & Feedback

If you like this project, consider giving it a ⭐ on GitHub!
Found a bug or have a feature request? Open an Issue or start a Discussion.
