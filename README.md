📄 SkillMatchAI – AI Powered Resume & Job Matcher


SkillMatchAI is an AI-powered career assistant built using Streamlit and Google Gemini.
It helps job seekers match resumes with job descriptions, generate ATS scores, perform SWOT analysis, and create customized resumes tailored for specific roles.
🌐 Live App: skillmatchai00.streamlit.app
----___
🚀 Features
📂 Upload resume (PDF) for instant text extraction
📋 Paste job description for skill matching
🤖 AI-powered ATS score estimation & keyword analysis
🔍 SWOT analysis of applicant’s profile
🎯 Probability of shortlisting prediction (%)
📝 Resume improvement suggestions
🆕 Auto-generate 2 customized resumes aligned with the job description
📄 One-page professional resume (Word/PDF ready)
----___
🎯 Target Users
🎓 Students & freshers applying for jobs/internships
💼 Professionals tailoring resumes for multiple roles
🧑‍💻 Recruiters seeking AI-assisted applicant evaluation
🎯 Career counselors helping candidates improve profiles
----___
🛠️ Tech Stack
Frontend: Streamlit (Python)
Backend: Google Gemini 2.5 Flash Lite API
Libraries:
streamlit
pandas
google-generativeai
pypdf
dotenv
----___
🏗️ Architecture
flowchart TD
    A[📂 Upload Resume (PDF)]
    B[📝 Extract Text with PyPDF]
    C[💻 Streamlit UI]
    D[📋 Job Description Input]
    E[🤖 Google Gemini 2.5 Model]
    F[🔍 Skill Matching & Insights]
    G[🆕 Customized Resume Generation]
    H[📄 Streamlit Output Display]

    A -->|___-___| B
    B -->|___-___| C
    D -->|___-___| C
    C -->|___-___| E
    E -->|___-___| F
    F -->|___-___| G
    G -->|___-___| H
----___
✨ SkillMatchAI empowers job seekers to create AI-tailored applications that maximize chances of getting shortlisted.
----___
🔥 Tagline:
"From Resume to Shortlist – Powered by AI"
