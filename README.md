# 🚀 AI Career Copilot

## Live Demo

https://ai-career-copilot-160688070605.europe-west1.run.app/

AI-powered tool that analyzes your resume against a job description and provides:

- ✅ Match score
- 📊 Skill gap analysis
- 💡 Improvement suggestions
- 📁 Downloadable PDF report

---

## 🧠 Features

- Resume parsing (PDF)
- Job description analysis
- AI-powered feedback (LLM)
- Vector search (embeddings)
- PDF report generation

---

## 🛠 Tech Stack

- Python
- Streamlit
- OpenAI API
- Docker
- Google Cloud Run

---

## 📦 Installation (Local)

```bash
git clone https://github.com/dejanjovic1283-ui/ai-career-copilot.git
cd ai-career-copilot
pip install -r requirements.txt

---

```bash
streamlit run app.py

---

## ☁️ Deployment (Google Cloud Run)

```bash
gcloud builds submit --tag gcr.io/ai-career-copilot-160688070605./ai-career-copilot

```bash
gcloud run deploy ai-career-copilot \
--image gcr.io/ai-career-copilot-160688070605./ai-career-copilot \
--platform managed \
--region europe-west1 \
--allow-unauthenticated

## 📌 Notes

Set your OPENAI_API_KEY in environment variables
Make sure Docker is installed for deployment

## 👨‍💻 Author
- Dejan Jovic

---
