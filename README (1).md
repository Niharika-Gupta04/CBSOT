# 🤖 Synora AI

An intelligent **Agentic AI Assistant** built using **Python, Flask, and Google's Gemini API**. Synora AI analyzes user queries, automatically selects the most suitable AI tool, and generates well-structured responses through a modern web interface.

---

## 📌 Overview

Synora AI demonstrates the concept of an **Agentic AI Model** by introducing a lightweight decision-making layer before generating responses. Instead of treating every prompt the same way, the application first determines the most appropriate tool for the user's request and then uses Gemini to produce a task-specific answer.

This project was developed as part of a **Machine Learning Internship**.

---

## ✨ Features

- 🧠 Agent-based tool selection
- 📚 Study Planner
- 📧 Email Writer
- 💻 Code Explainer
- 🐞 Code Debugger
- 📝 Text Summarizer
- 💬 General AI Assistant
- 🎨 Modern and responsive UI
- 📄 Markdown-formatted responses
- ⚡ Powered by Google Gemini 2.5 Flash

---

## 🛠️ Tech Stack

- Python
- Flask
- Google Gemini API
- HTML5
- CSS3
- JavaScript
- Markdown

---

## 📂 Project Structure

```
Synora-AI/
│
├── app.py
├── requirements.txt
├── .gitignore
│
├── static/
│   ├── style.css
│   └── script.js
│
├── templates/
│   └── index.html
│
└── utils/
    ├── agent.py
    └── prompts.py
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/sanya-1612/Synora-AI.git
cd Synora-AI
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Create a `.env` file

```env
GEMINI_API_KEY=YOUR_API_KEY
```

### Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 🚀 Example Prompts

- Write a leave application for college.
- Explain Binary Search with C++.
- Create a 30-day Machine Learning roadmap.
- Summarize the importance of Artificial Intelligence.
- Help me debug my Python code.

---

## 🧠 How It Works

```
User Input
     │
     ▼
Agent Decision Layer
     │
     ▼
Tool Selection
     │
     ▼
Gemini API
     │
     ▼
Formatted Response
```

---

## 🔮 Future Improvements

- LLM-based intelligent routing
- Conversation memory
- Voice interaction
- File upload support
- Multi-agent collaboration
- Deployment on cloud platforms

---

## 👩‍💻 Author

**Sanya Singh**

GitHub: https://github.com/sanya-1612

---

## 📄 License

This project is intended for educational and learning purposes.
