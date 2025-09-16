# 📄 Smart Resume Parser with ATS Score Predictor  

🚀 An AI-powered web application that parses resumes, compares them with job descriptions, and predicts ATS match scores with skill gap analysis.  

---

## 📖 About the Project  

**Smart Resume Parser with ATS Score Predictor** is a Python-based web app that helps candidates analyze and optimize their resumes for Applicant Tracking Systems (ATS).  

The system:  
- Parses resumes in **PDF/DOCX/TXT** format  
- Extracts key details like **name, email, phone, skills, education, and experience**  
- Compares extracted information with a **job description (JD)**  
- Generates an **ATS Match Score (%)** using **TF-IDF (cosine similarity)** and **skill matching**  
- Suggests **missing skills** to improve alignment with the JD  
- Provides a **downloadable JSON report** with all results  

This project demonstrates expertise in **Natural Language Processing (NLP)**, **Machine Learning**, and **Streamlit web development**.  

---

## ✨ Features  
- 📄 Resume Parsing (PDF, DOCX, TXT)  
- 🤖 ATS Match Score prediction  
- 💡 Skill Gap Analysis (missing skill suggestions)  
- 📊 Interactive Streamlit dashboard  
- 📥 JSON Report Export  

---

## 🛠 Tech Stack  
- **Python 3.9+**  
- **Streamlit** – Web application framework  
- **spaCy** – NLP processing  
- **scikit-learn** – TF-IDF & cosine similarity  
- **pdfplumber / python-docx** – Resume parsing  
- **Regex** – Contact info & education extraction  

---

## ⚙️ Installation & Setup  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/smart-resume-parser.git
   cd smart-resume-parser

