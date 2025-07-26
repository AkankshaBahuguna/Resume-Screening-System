# Resume-Screening-System
A group project which was given by IBM during Summer Intership 2025

# 📄 Resume Screening System (ATS Powered)

This is a Resume Screening System built with **Streamlit** that automates resume evaluation based on ATS (Applicant Tracking System) principles. It parses resumes, analyzes skills, and compares candidates based on a provided dataset or individual resume upload.

---

## 🚀 Features

- 📤 Upload a **CSV dataset of resumes**
- 📊 ATS scoring and resume parsing using NLP
- 📈 Visual visualizations using Plotly
- 💡 Skill extraction, keyword matching
- 📥 Export refined results as CSV
- 🌐 Simple and intuitive **Streamlit** web interface

---

## 📂 Folder Structure
resume/
│
├── ats system/
│ ├── app.py # Main Streamlit app
│ ├── text_extractor.py # Resume text extraction
│ ├── utils.py # Helper functions
│
├── resume_dataset.csv # Resume dataset (CSV)
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml


---

## 🧑‍💻 How to Run the Project

### 🔧 Prerequisites

- Python 3.8+
- pip (Python package manager)

### 📦 Install Required Packages

```bash
pip install -r requirements.txt
▶️ Run the Streamlit App
bash

streamlit run "ats system/app.py"
Then open your browser at:
👉 http://localhost:8501

📊 Dataset Format
The input CSV dataset should contain at least the following columns:

Name

Email

Resume_text

Skills (optional)

Each row represents one candidate’s resume content.

🛠 Tech Stack
Python

Streamlit

Plotly

scikit-learn

spaCy / NLTK for NLP

pandas, NumPy

💡 Future Enhancements
🧠 AI-based job fit scoring

📄 Upload job descriptions for JD-to-resume match

📎 Upload and parse multiple resume PDFs

🔐 Login & user dashboard for tracking past uploads

📤 Export ATS reports in PDF/Docx format

🧑‍🎓 Developed By
Akanksha Bahuguna




