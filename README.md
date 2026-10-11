# AI ATS Resume Analyzer

A simple, AI-assisted ATS-style tool that compares a **resume** with a **job description** and produces:

- An estimated **match score**
- **Matched keywords**
- **Missing keywords** (potential gaps)
- A view of top keywords in the resume

> ⚠️ This is a learning project, not a production ATS used by companies.  
> It is designed to showcase **Python, automation, and basic NLP** skills.

---

## 🚀 Features (V1)

- Upload resume (PDF / DOCX)
- Paste JD or upload JD (PDF / TXT)
- Keyword-based match scoring
- Missing keyword suggestions
- Clean Streamlit UI

Planned for V2:
- AI-generated improved bullet points and summary
- Match score explanation using LLM
- PDF/HTML report export via `report_generator.py`

---

## 🧱 Tech Stack

- **Python 3**
- **Streamlit** – UI
- **pdfplumber**, **python-docx** – text extraction
- Basic NLP using tokenization & keyword analysis

---

## ▶️ Run Locally

```bash
git clone https://github.com/akshatrai1612/AI-ATS-Resume-Analyzer.git
cd AI-ATS-Resume-Analyzer

python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows

pip install -r requirements.txt
streamlit run app.py
