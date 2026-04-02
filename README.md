# 🤖 AI Resume Screening Application

## 📌 Overview

This project is an AI-powered resume screening application that automates candidate evaluation by comparing resumes with job descriptions. It uses a Large Language Model (LLM) to analyze skills, experience, and overall suitability, helping streamline the hiring process.

---

## 🚀 Features

* 📄 Upload resumes in PDF format
* 🧠 Extract and process resume content
* 📋 Analyze job descriptions
* 📊 Generate candidate scores and feedback
* ⚡ Fast backend API for processing
* 🖥️ Interactive web UI

---

## 🛠️ Tech Stack

* **Backend:** FastAPI
* **Frontend:** Streamlit
* **AI Model:** GPT-4 (OpenAI API)
* **Server:** Uvicorn
* **Language:** Python

---

## ⚙️ How It Works

1. User uploads a resume (PDF format)
2. System extracts text from the resume
3. Job description is processed
4. Structured input is sent to the LLM
5. AI evaluates the candidate and returns:

   * Score
   * Skill match
   * Feedback
6. Results are displayed in the UI

---

## 📂 Project Structure

```
project/
│── app/
│   ├── main.py        # FastAPI backend
│   ├── agents/        # AI processing modules
│   ├── utils/         # Helper functions
│
│── ui/
│   ├── app.py         # Streamlit UI
│
│── requirements.txt
│── README.md
```

---

## ▶️ Installation & Setup

### 1. Clone the repository

```
git clone <your-repo-link>
cd project
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run Backend Server

```
uvicorn app.main:app --reload
```

### 4. Run Frontend UI

```
cd ui
streamlit run app.py
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory and add:

```
OPENAI_API_KEY=your_api_key_here
```

---

## 📊 Sample Output

* Candidate Score: 78/100
* Matching Skills: Python, Machine Learning
* Feedback: Strong technical background but needs improvement in system design

---

## 💡 Future Improvements

* Add Resume Ranking (multiple candidates)
* Implement RAG for better accuracy
* Export evaluation report as PDF
* Improve UI with visual analytics

---

## 🎯 Use Cases

* HR recruitment automation
* Resume shortlisting
* Candidate skill analysis

---

## 👨‍💻 Author

Developed as a beginner-friendly Generative AI project to demonstrate real-world AI application development.

---
