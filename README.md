📄 SkillMatchAI – AI-Powered Resume & Job Description Matcher
SkillMatchAI is an AI-powered career assistant built with Streamlit and Google Gemini.
It analyzes resumes (PDFs) and compares them against job descriptions to generate ATS scores, keyword matches, SWOT analysis, and even customized resumes tailored for specific roles.
🚀 Features
📂 Upload your resume (PDF) for instant text extraction
📋 Paste a job description for skill matching
🤖 AI-powered ATS score estimation & keyword match analysis
🔍 SWOT analysis of the applicant’s profile
🎯 Probability of shortlisting prediction (in %)
📝 Resume improvement suggestions
🆕 Auto-generate 2 customized resumes aligned with the job description
📄 One-page professional resume ready for PDF/Word export
🎯 Target Users
Students & freshers applying for jobs/internships
Professionals tailoring resumes for multiple roles
Recruiters seeking AI-assisted applicant evaluation
Career counselors helping candidates improve profiles
🛠️ Tech Stack
Frontend: Streamlit (Python)
Backend: Google Gemini 2.5 Flash Lite API
Libraries:
streamlit
pandas
google-generativeai
pypdf (for PDF parsing)
dotenv (for API key management)
🏗️ Architecture
flowchart TD
    A[Upload Resume (PDF)] --> B[Text Extractor using PyPDF]
    B --> C[Streamlit UI]
    D[Job Description Input] --> C
    C --> E[Google Gemini Model]
    E --> F[Skill Matching & Insights]
    F --> G[Customized Resume Generation]
    G --> H[Streamlit Output Display]
