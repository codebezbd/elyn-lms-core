# 🎓 Elyn LMS Core

Welcome to the **Elyn LMS Core**, the custom-built Learning Management System for [courses.elynbd.com](https://courses.elynbd.com).  
This project is designed to empower Bangla Medium learners with a fully tailored, gamified, and tutor-free educational experience.

---

## 🔧 Tech Stack

- **Language:** Python 3.12+
- **Framework:** Django 5.x
- **Database:** PostgreSQL
- **Frontend:** HTML, CSS (Tailwind/Bootstrap optional), Vanilla JS
- **Others:** Git, GitHub, VS Code

---

## 🚀 Project Goal

To build a **custom LMS** that goes beyond traditional platforms by including:

- 🎮 Game-based learning modules (quizzes, flashcards)
- ⚔️ One-on-one learner challenges
- 🏆 Leaderboards and point systems
- 🔐 Secure back-end with PostgreSQL
- 🧑‍🎓 Course tracking and student progress
- 🖼️ Visual and interactive content aligned with **ElynBD’s mission**

---

## 📁 Folder Structure
```
elyn-lms-core/
├── manage.py
├── lms_core/        # Django project settings
├── accounts/        # User management
├── courses/         # Course modules
├── quizzes/         # Quiz & challenge logic
├── templates/       # HTML Templates
├── static/          # CSS/JS/Images
├── .env             # Environment variables
├── .gitignore
└── README.md
```

---

## 🛠️ Local Development Setup

### 1. Clone the Repository

```bash
git clone https://github.com/codebezbd/elyn-lms-core.git
cd elyn-lms-core
```

### 2. Set Up Virtual Environment

```bash
python -m venv env
source env/bin/activate  # For Linux/macOS
env\Scripts\activate     # For Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file using `.env.example` and fill in your PostgreSQL credentials.

### 5. Set Up PostgreSQL Database

```bash
# Create DB and user manually or using pgAdmin / psql
```

### 6. Run Migrations

```bash
python manage.py migrate
```

### 7. Start Development Server

```bash
python manage.py runserver
```

---

## 📌 Contribution Guidelines (Future)

- All development should be tracked using **GitHub issues and branches**
- Branch naming convention: `feature/`, `fix/`, `refactor/`
- All code must be tested before push

---

## 📜 License

This project is licensed under the **MIT License** — see `LICENSE.md` for details.

---

## 🌐 Credits

Created by Founder of [ElynBD.com](https://elynbd.com)  
GitHub: [codebezbd](https://github.com/codebezbd)
