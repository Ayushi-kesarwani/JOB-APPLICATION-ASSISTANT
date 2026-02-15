📘 Project Documentation
Job Application Assistant Chatbot
1. Problem Statement

Many students and freshers apply for jobs without knowing whether their resume actually matches the job requirements. They often lack clarity about missing skills, resume gaps, and expected salary, which leads to repeated rejections and confusion during placement preparation.

There is a need for an intelligent system that can:

Analyze a resume against a job description

Identify skill gaps

Provide clear guidance and answers to job-related queries

Do all this in a cost-effective and reliable way

2. Objective of the Project

The main objectives of this project are:

To analyze a candidate’s resume with respect to a given job description

To calculate a job fit score based on matching skills

To identify missing skills required for the job

To provide resume-aware job-related guidance through a chatbot

To build a completely free solution without using paid APIs

To reduce AI hallucination by using a hybrid rule-based and AI approach

3. Scope of the Project

This project can be used by:

Students preparing for placements

Freshers applying for entry-level roles

Learners who want to understand skill gaps for a job role

The system is designed for career guidance and educational purposes and not for final hiring decisions.

4. System Architecture
High-Level Architecture
User
 ↓
Streamlit UI
 ↓
Resume Upload (PDF) + Job Description
 ↓
Resume Text Extraction (PyPDF)
 ↓
Skill Matching & Fit Score Calculation
 ↓
Hybrid Logic Layer
   ├── Rule-based logic (Salary estimation)
   └── AI-based logic (Job-related Q&A)
 ↓
Result Display to User

5. Module Description
5.1 User Interface Module

Built using Streamlit

Allows users to:

Upload resume (PDF)

Paste job description

View analysis results

Ask job-related questions

5.2 Resume Parsing Module

Uses PyPDF

Extracts text from uploaded resume

Converts resume content into processable text format

5.3 Skill Matching Module

Predefined skill list is used

Compares resume skills with job description skills

Generates:

Matching skills

Missing skills

Job fit score (percentage)

5.4 Chatbot Module

Uses an open-source language model (distilGPT-2)

Answers general job-related questions

Provides interview guidance and resume tips

5.5 Rule-Based Salary Estimation Module

Salary-related questions are handled using deterministic rules

Avoids AI hallucination and unreliable numeric predictions

Improves trust and consistency of output

6. Technology Used
Technology	Purpose
Python	Core programming language
Streamlit	Web application framework
PyPDF	Resume text extraction
Transformers (HuggingFace)	AI model integration
distilGPT-2	Open-source text generation model
Rule-based Logic	Reliable salary estimation
7. Algorithm / Workflow

User uploads resume in PDF format

Resume text is extracted

User enters job description

Skills are matched between resume and job description

Job fit score is calculated

Matching and missing skills are displayed

User asks job-related questions

System responds using:

Rule-based logic for salary

AI-based logic for other questions

8. Output / Results

The system provides:

Job fit score (%)

List of matching skills

List of missing skills

Suggestions for skill improvement

Answers to job-related questions

Salary range estimation for freshers

9. Unique Features of the Project

Resume-aware chatbot (context-based answers)

Explainable job fit score

Hybrid intelligence (AI + rule-based)

Completely free and cost-efficient

No API key or paid services required

Placement-focused real-world application

10. Limitations

Uses a lightweight AI model, so answers may be generic

Does not provide real-time company-specific salary data

Accuracy depends on the quality of resume and job description text

Designed for guidance, not final hiring decisions

11. Future Enhancements

ATS resume score calculation

Advanced skill extraction using NLP

Better instruction-following open-source models

Resume improvement suggestions with examples

User authentication and resume history

Cloud deployment

12. Conclusion

The Job Application Assistant Chatbot is a practical and user-friendly system that helps students and job seekers understand their job readiness. By combining resume analysis, skill gap identification, and a hybrid AI approach, the project provides reliable career guidance while remaining completely free and accessible.

13. References

HuggingFace Transformers Documentation

Streamlit Documentation

PyPDF Documentation
