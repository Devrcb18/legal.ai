# Legal.AI 🏛️

Legal.AI is a web application powered by **FastAPI** and **LLMs** that provides:
- ✨ Legal **advice summaries** (informational only, not a substitute for professional legal services)  
- 📑 Auto-generated **legal document drafts** tailored to the user’s country  

It integrates with the **Hugging Face Inference API** to generate content, and has a simple frontend served by FastAPI.

---

## 🚀 Features
- Advice Mode → concise step-by-step guidance based on country and case description  
- Document Mode → auto-generate `.docx` legal templates (agreements, complaints, notices, etc.)  
- Health check endpoint (`/api/health`)  
- Static frontend served with backend (`/`, `/img/...`)  

---

## 🛠️ Tech Stack
- **Backend**: FastAPI + Uvicorn  
- **Frontend**: Static HTML/JS/CSS (served by FastAPI)  
- **LLM**: Hugging Face OpenAI-compatible API  
- **Other**: python-docx, python-dotenv  

---

## 📂 Project Structure

Legal.ai
├── backend/
│ ├── main.py 
│ ├── requirements.txt 
│ └── env.example 
│
└── frontend/ 
├── index.html
└── images/
└── photo





---

## ⚙️ Setup & Installation

### 1. Clone the repo
```bash
git clone https://github.com/your-username/legal-ai.git
cd legal-ai
