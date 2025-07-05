# 🗣️ Feedback App

A simple and secure web-based **Feedback Collection App** that allows users to submit feedback, and admins to view and manage submissions in an organized format. Perfect for internships, events, product testing, or user surveys.

---

## 🚀 Features

- 📝 User-friendly feedback form (name, email, comments, ratings)
- 🧾 Stores feedback data securely (in database or JSON file)
- 📊 Admin dashboard to view, filter, and analyze responses
- ✅ Validation for clean inputs
- 📧 Optional email notifications on submission

---

## 🛠 Tech Stack

- **Python (Flask)** or **Django**
- **HTML5**, **CSS3**, **Bootstrap**
- **SQLite** / **MySQL** for storage
- *(Optional)* `WTForms` for validation or `SMTP` for email

---

## 📁 Folder Structure
feedback_app/
├── app.py / views.py # Main backend logic
├── templates/
│ └── feedback_form.html # User feedback page
│ └── admin_dashboard.html # Admin view
├── static/ # CSS, images
├── feedback.db / feedback.json # Feedback storage
└── README.md

---

## ⚙️ How to Run

### 🔧 Step 1: Install Dependencies

```bash
pip install flask
Step 2: Run the App
python app.py

