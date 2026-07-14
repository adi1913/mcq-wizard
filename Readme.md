# 🧠 MCQ Wizard

An AI-powered web application that transforms PDF and DOCX study materials into high-quality Multiple Choice Questions (MCQs) using **Google Gemini AI**.

Transform your study material into **Multiple Choice Questions (MCQs)** in seconds.

✅ Upload your notes
✅ Choose how many questions you want
✅ Review & edit MCQs
✅ Download in PDF, DOCX, or TXT format

---

# 📚 Table of Contents

* About
* Features
* Tech Stack
* Getting Started
* How It Works
* Project Structure
* Future Enhancements
* Contributing
* License

---

# 📖 About

**MCQ Wizard** is an AI-powered full-stack web application that automatically generates multiple-choice questions from PDF or DOCX documents. It leverages **Google Gemini AI** through a **FastAPI** backend and provides a clean **React** frontend for uploading files, reviewing generated questions, editing them, and exporting them in multiple formats.

The project is designed for students, teachers, educators, and e-learning platforms to simplify the process of creating quizzes from study materials.

---

# ✅ Features

* 📂 Upload PDF and DOCX files
* 🤖 AI-powered MCQ generation using Google Gemini
* 🎯 Generate a custom number of questions
* 📝 Edit generated questions and answer options
* ❌ Delete unwanted questions
* ✅ Approve or reject questions
* 👀 Live preview before downloading
* 📄 Export MCQs as PDF
* 📑 Export MCQs as DOCX
* 📃 Export MCQs as TXT
* ⚡ FastAPI backend with robust error handling
* 🌐 Responsive React frontend

---

# 🛠 Tech Stack

## Frontend

* React
* Vite
* Tailwind CSS
* JavaScript

## Backend

* Python
* FastAPI
* Google Gemini API

## Libraries

* PyPDF2
* python-docx
* python-multipart
* jsPDF
* html-docx-js

---

# ⚙️ Getting Started

## Prerequisites

* Node.js
* npm
* Python 3.10+
* pip
* Google Gemini API Key

---

## 1. Clone Repository

```bash
git clone https://github.com/adi1913/mcq-wizard.git

cd mcq-wizard
```

---

## 2. Backend Setup

```bash
cd backend

python -m venv venv
```

### Activate Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

Start FastAPI

```bash
uvicorn main:app --reload
```

Backend runs on

```
http://localhost:8000
```

---

## 3. Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on

```
http://localhost:5173
```

---

# 🚀 How It Works

### Step 1

Launch the application.

### Step 2

Upload a PDF or DOCX document.

### Step 3

Choose the number of MCQs you want to generate.

### Step 4

The backend extracts text and sends it to Google Gemini AI.

### Step 5

Review, edit, approve, or delete generated questions.

### Step 6

Download the final MCQs as:

* PDF
* DOCX
* TXT

---

# 📂 Project Structure

```text
mcq-wizard
│
├── backend
│   ├── main.py
│   ├── requirements.txt
│   └── ...
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── assets
│   │   ├── components
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── package.json
│   └── vite.config.js
│
├── README.md
├── screenshots.md
└── Screenshots
```

---

# 🚀 Future Enhancements

* 🔐 User Authentication
* 📊 Dashboard for generated MCQs
* 🌍 Multi-language support
* 🔁 Question regeneration
* 📈 Usage analytics
* 🧠 Better distractor generation
* ☁️ Cloud deployment
* 📝 MCQ history management

---

# 🤝 Contributing

Contributions are welcome.

To contribute:

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

Bug reports, feature requests, and suggestions are appreciated.

---

# 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
