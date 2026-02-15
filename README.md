# JOB-APPLICATION-ASSISTANT
# Job Application Assistant Chatbot

An AI-powered, resume-aware chatbot that helps job seekers analyze their resume against a job description, calculate job fit score, identify skill gaps, and answer job-related questions — all without using any paid API.

---

## 🚀 Features

- 📄 Resume Upload (PDF)
- 📊 Resume vs Job Description Analysis
- ✅ Job Fit Score (%)
- ✔ Matching Skills Identification
- ❌ Missing Skills Detection
- 💡 Skill Improvement Suggestions
- 💬 Job-related Question Answering
- 💰 Rule-based Salary Estimation
- 🔒 Completely Free & Local AI (No API Key)

---

## How It Works

1. User uploads their resume (PDF)
2. User pastes a job description
3. System extracts text from resume
4. Skills are matched against job requirements
5. A fit score is calculated
6. Chatbot answers user queries using a lightweight open-source language model
7. Sensitive answers like salary are handled using rule-based logic to avoid AI hallucinations

---

## 🛠️ Tech Stack

- **Language:** Python
- **Frontend:** Streamlit
- **Resume Parsing:** PyPDF
- **AI Model:** distilGPT-2 (HuggingFace)
- **Logic:** Hybrid (Rule-based + AI)

---

## 📦 Installation

```bash
pip install streamlit pypdf transformers torch

▶️ Run the Project
streamlit run app.py


Open in browser:

http://localhost:8501

🧪 Example Questions You Can Ask

Am I suitable for this job?

What skills are missing in my resume?

How can I improve my resume?

What interview questions can be asked for this role?

How much salary can I expect as a fresher?

🌟 What Makes This Project Unique?

Resume-aware chatbot (answers depend on uploaded resume)

Explainable fit score instead of black-box output

Hybrid intelligence (AI + rule-based logic)

Completely free and cost-efficient

Placement-focused real-world use case

⚠️ Limitations

Uses a lightweight open-source model, so answers may be generic

Does not provide real-time company-specific salary data

Intended for educational and career guidance purposes

🔮 Future Enhancements

ATS resume score calculation

Better instruction-following open-source models

Resume improvement suggestions with examples

User login and resume history

Cloud deployment

🎓 Ideal For

Final year projects

Placement preparation

Resume screening practice

AI/ML learning demonstrations

📜 License

This project is developed for educational purposes only.
