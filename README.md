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
