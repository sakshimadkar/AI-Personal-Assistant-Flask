# 🤖 AI Personal Assistant — Flask

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.x-black?style=for-the-badge&logo=flask&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-LLM-412991?style=for-the-badge&logo=openai&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 Project Overview

**AI Personal Assistant** is a full-stack web application that brings the power of large language models directly into your browser. Built with **Python & Flask** on the backend and a clean **HTML/CSS** frontend, it helps users automate everyday tasks — from drafting professional emails to summarizing long text — all through a simple, intuitive interface.

> No complex setup. Just ask, and the AI handles the rest.

---

## 🚀 Key Features

- 💬 **Ask Anything** — Get instant, context-aware answers to any question using OpenAI's language models
- 📧 **Email Summarizer** — Paste any email and receive a concise 2–3 sentence summary in seconds
- ⚡ **Real-time AI Responses** — Streamed text generation with zero page reloads (AJAX-powered)
- 🎨 **Clean, Responsive UI** — Minimal and distraction-free interface that works across devices
- 🔐 **Secure API Key Handling** — API keys stored safely in `.env`, never exposed to the frontend

---

## 📸 Screenshots

### Main Interface
![App Overview](screenshots/screenshot1.png)

### Ask Anything — AI Response
![Ask Feature](screenshots/screenshot2.png)

### Summarize Email — Output
![Summarize Feature](screenshots/screenshot3.png)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Python 3.10+, Flask |
| **Frontend** | HTML5, CSS3 |
| **AI / LLM** | OpenAI API (`gpt-4o`) |
| **Config** | python-dotenv |
| **HTTP Client** | OpenAI Python SDK |

---

## ⚙️ How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/sakshimadkar/AI-Personal-Assistant-Flask.git
cd AI-Personal-Assistant-Flask
```

### 2. Create & Activate a Virtual Environment

```bash
# Create virtual environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on Mac/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a `.env` file in the project root:

```bash
OPENAI_API_KEY=your_openai_api_key_here
```

> 🔑 Get your API key from [OpenAI Platform](https://platform.openai.com/api-keys) or use a Groq-compatible key.

### 5. Run the Application

```bash
python main.py
```

Open your browser and navigate to: **http://127.0.0.1:5000**

---

## 📁 Project Structure

```
AI-Personal-Assistant-Flask/
│
├── main.py               # Flask app — routes & API logic
├── templates/
│   └── index.html        # Frontend HTML template
├── static/
│   └── style.css         # Stylesheet
├── screenshots/          # App preview images
├── .env                  # API keys (not committed)
├── .gitignore
└── README.md
```

---

## 👩‍💻 Author

**Sakshi Madkar**
[![GitHub](https://img.shields.io/badge/GitHub-sakshimadkar-181717?style=flat&logo=github)](https://github.com/sakshimadkar)

---

> ⭐ If you found this project useful, consider giving it a star!