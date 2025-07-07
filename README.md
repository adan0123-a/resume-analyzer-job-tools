# Resume Analyzer + Job Tools

An AI-powered resume analyzer and job finder app built using Streamlit, SpaCy, HuggingFace Transformers, and the JSearch API.

## 🚀 Features

- 📄 Upload resume (PDF)
- 🧠 Extract skills and quantified achievements
- 🔍 Match skills with real job listings using JSearch (RapidAPI)
- ✍️ Auto-generate professional cover letters using FLAN-T5
- 💡 Provide resume improvement tips

## 🛠️ Tech Stack

- Python 3.8+
- Streamlit
- HuggingFace Transformers (FLAN-T5, BART-MNLI)
- SpaCy (en_core_web_sm)
- PyPDF2
- Requests (for job API 465207987emsh4f9672ddf267621p1c87dajsn13d61aa4fe05)
- streamlit-option-menu

## 📦 Installation

```bash
git clone https://github.com/adan0123-a/resume-analyzer-job-tools.git
cd resume-analyzer-job-tools
pip install -r requirements.txt
streamlit run app.py
