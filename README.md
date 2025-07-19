# 🚀 Resume Analyzer based on Job Description (JD)

This project is a smart, interactive **Resume Analyzer** built with **Gradio**, **OCR**, and **NLP** tools. It helps job seekers evaluate their resume's compatibility with specific job descriptions by calculating an **ATS (Applicant Tracking System) match score** and suggesting the most suitable job roles based on detected skills.

## 🔍 Features

- ✅ Extracts text from PDF resumes using OCR (pytesseract & pdf2image)
- 🧠 Analyzes resumes for relevant **keywords** and **skills**
- 📊 Calculates ATS match score with a pie chart visualization
- 🧩 Matches resume with the most relevant tech roles (AI/ML, Web Dev, Data Science, etc.)
- 🌟 Gives role recommendations & improvement tips
- ⚡️ Interactive UI using Gradio

## 🛠️ Technologies Used

- `Python`, `Gradio`, `PyMuPDF`, `pdf2image`, `pytesseract`
- `NLTK` for keyword extraction
- `Matplotlib` for score visualization

## 📦 Roles Supported

Includes skill-based evaluation for roles like:
- AI/ML Intern
- Data Analyst
- Web Developer
- Backend Developer
- Cloud Engineer
- DevOps Engineer
- Cybersecurity Analyst
- Data Scientist
- Business Analyst
- Full Stack Developer

## 🚀 How to Use

1. Run the script in a Python environment (or Google Colab).
2. Upload your **resume** (PDF).
3. Paste the **job description** text.
4. View your ATS score, pie chart, and role-fit suggestions.

## 🧪 Demo

The app launches a **Gradio** interface locally or via public sharing link. Customize it further to suit your resume parsing or ATS scoring needs.
