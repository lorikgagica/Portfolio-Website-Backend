# 🌐 Feedback & Contact Flask Web App

A simple web application built with Flask, offering a **contact form** for users to send feedback, and a **feedback display** page to view all submitted responses. Perfect for adding communication features or testing basic web form workflows!

---

## ✨ Features

- **Contact page** with fields: Name, Email, Message
- **Feedback submission endpoint** (`/submit-feedback`): POSTs form data
- **Stores feedback in a local JSON file** (`feedback.json`)
- **Feedback display page:** Shows all name/email/message entries in a list
- **Minimal, clean HTML for easy customization**
- **Flask-powered routing for home, contact, and feedback pages**
- **Easy-to-read server and client code—great for beginners!**

---

## 🚀 How to Run

1. **Install Python 3**
2. **Install Flask:**
    ```
    pip install flask
    ```
3. **Save all files (`app.py`, `contact.html`, `feedback.html`) and place them in the correct templates folder:**
    - Place HTML files in `templates/` directory
    - Place `app.py` at the project root

4. **Run the server in terminal:**
    ```
    python app.py
    ```

5. **Visit your app in a browser:** `http://localhost:5000`
    - `/contact` for the contact form
    - `/feedback` to view submitted feedbacks

---

## 📁 File Structure

project_folder/
|
|-- app.py
|-- feedback.json (created after first submission)
|-- templates/
|-- contact.html
|-- feedback.html
|-- index.html (default home)

---

## 🧑‍💻 Usage

- **Contact page:** Fill out name/email/message, click Submit
- **Feedback page:** See all feedback from all users
- **Data persistence:** All feedback saved to a local JSON file (`feedback.json`)

---

## 🗂️ How It Works

- Contact form sends a POST request to `/submit-feedback`
- Server receives data, appends to JSON file
- `/feedback` route loads all feedbacks and renders them in HTML

---

## 📄 License

MIT License — free for learning, teaching, and tinkering.

---

A neat template for Flask form handling—customize and extend for any simple project!
