# Agriculture-AI-chatbot


# 🧠 Legal Document / Chatbot Web Application

A Flask-based intelligent chatbot web application that allows users to chat with an AI-powered model, save their chat history, and provides an admin dashboard for monitoring and exporting conversations.

---

## 🚀 Features

### 👤 User Side

* **User Registration & Login** — Secure user authentication using Flask sessions.
* **Chat Interface** — Users can send messages and get AI responses in real time.
* **Multilingual Support** — Messages can be translated to the selected language.
* **Chat History** — Users’ messages are stored and displayed during subsequent logins.

### 🔐 Admin Side

* **Admin Login** — Protected admin area for management.
* **Dashboard** — View all user chat histories.
* **Search & Filter** — Search by username, message, or response.
* **Export Chat Data** — Download complete chat history as a CSV file.
* **Clear History** — Delete all chat data from the database.

---

## 🧩 Project Structure

```
├── app.py                 # Main Flask application
├── database.py            # Database models and initialization
├── chatbot_model.py       # AI model for generating responses
├── templates/             # HTML templates (index, register, chat, admin pages)
├── static/                # CSS, JS, and other static files
└── agri_chatbot.db        # SQLite database (auto-created)
```

---

## ⚙️ Technologies Used

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Database:** SQLite (via SQLAlchemy ORM)
* **AI/ML Model:** Custom chatbot model (`chatbot_model.py`)
* **Admin Tools:** CSV Export, Chat History Management

---

## 🧰 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Then open your browser and visit:
👉 **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**

---

## 🔑 Default Admin Credentials

| Username | Password |
| -------- | -------- |
| admin    | admin123 |

---

## 💾 Database

The application automatically creates an SQLite database named `agri_chatbot.db`.
You can inspect it using any SQLite browser tool or command line.

---

## 🧠 Chatbot Functionality

The chatbot logic is handled in `chatbot_model.py`:

* Processes user queries using NLP or predefined logic.
* Can include translation or domain-specific responses (like legal or agriculture-related queries).

---

## 📦 Future Enhancements

* Integrate Google Cloud AI or OpenAI APIs for improved responses.
* Add user analytics (conversation length, usage trends).
* Enable file uploads for document-based question answering.

---

## 🧑‍💻 Author

**Mudula Savitri**
📧 [mudulasravani@gmail.com](mailto:mudulasravani@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/savitri-mudula-183b9932b/) | [GitHub](https://github.com/Mudula-Sravani)

---

## 🪪 License

This project is open-source and available under the [MIT License](LICENSE).
