📄 SkillMatchAI – AI Powered Resume & Job Matcher


SkillMatchAI is an AI-powered career assistant built with Streamlit and Google Gemini.
It analyzes resumes and job descriptions to generate ATS scores, keyword matches, SWOT analysis, and even customized resumes tailored for specific roles.

🌐 Live App: skillmatchai00.streamlit.app


🚀 Features

📂 Upload resume (PDF) for instant text extraction
📋 Paste job description for skill matching
🤖 AI-powered ATS score estimation & keyword analysis
🔍 SWOT analysis of applicant’s profile
🎯 Probability of shortlisting prediction (%)
📝 Resume improvement suggestions
🆕 Auto-generate 2 customized resumes aligned with the job description
📄 One-page professional resume (Word/PDF ready)

🎯 Target Users

🎓 Students & freshers applying for jobs/internships
💼 Professionals tailoring resumes for multiple roles
🧑‍💻 Recruiters seeking AI-assisted applicant evaluation
🎯 Career counselors helping candidates improve profiles
🛠️ Tech Stack

Frontend:

Streamlit (Python)

Backend:

Google Gemini 2.5 Flash Lite API

Libraries:

streamlit
pandas
google-generativeai
pypdf
dotenv


🏗️ Architecture

flowchart TD
    A[Upload Resume (PDF)] --> B[Text Extractor: PyPDF]
    B --> C[Streamlit UI]
    D[Job Description Input] --> C
    C --> E[Google Gemini Model]
    E --> F[Skill Matching & Insights]
    F --> G[Customized Resume Generation]
    G --> H[Streamlit Output Display]
✨ With SkillMatchAI, job seekers can go beyond static resumes and create AI-tailored applications that boost their chances of getting shortlisted.
🔥 Tagline:
“From Resume to Shortlist – Powered by AI”
