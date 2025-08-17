# TDS_DATA_ANALYST_AGENT

[![FastAPI](https://img.shields.io/badge/FastAPI-Ready-brightgreen)](https://fastapi.tiangolo.com/)  
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

---

## 🔥 **Data Analyst Agent**  
A **data analysis engine** built with **FastAPI**, **LangChain**, and **Google Generative AI**, delivering **instant insights, visualizations, and summaries** from any dataset.  

✔ **Conversational Queries → Structured Answers**  
✔ **Dynamic Visual Reports**  
✔ **Secure & Local Processing**  

---

## 🌟 **Why Choose This?**  

| Feature                | Benefit |
|------------------------|---------|
| ✅ AI-driven Analysis  | Understands plain English queries |
| ✅ Live Web Scraping   | Pulls real-time data from URLs |
| ✅ Multi-format Input  | CSV, Excel, JSON, Parquet |
| ✅ Visual Power        | Seaborn & Matplotlib charts |
| ✅ Ultra-Fast Backend  | Built on FastAPI |

---

## 🛠 **How It Works**  
1. **Prepare Your Questions** – Write them in a `.txt` file  
2. **Upload Dataset + Questions** – CSV/Excel + Query file  
3. **Get AI Insights** – Visuals + Answers + Correlations  

---

## 🚀 **Installation**  

### **Clone the Repository**
\`\`\`bash
git clone https://github.com/your-username/ai-data-analyst-pro.git
cd ai-data-analyst-pro
\`\`\`

### **Install Requirements**
\`\`\`bash
pip install -r requirements.txt
\`\`\`

### **Set Environment Variables**
Create `.env` file:
\`\`\`
GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240
\`\`\`

### **Run the App**
\`\`\`bash
uvicorn app:app --reload
\`\`\`

Access at: **http://localhost:8000/**  

---

## 📡 **Endpoints**  
| Method | Path       | Description |
|--------|-----------|-------------|
| GET    | `/`        | Web UI |
| POST   | `/api`     | Analyze data |
| GET    | `/summary` | Diagnostics |

---

## 🧩 **Tech Stack**  
- **FastAPI** – High-performance backend  
- **LangChain** – AI orchestration  
- **Google Generative AI** – LLM brain  
- **Pandas, NumPy** – Data wrangling  
- **Matplotlib, Seaborn** – Visualizations  

---

## 🔐 **Security**  
✔ Local-only data processing  
✔ API keys hidden in `.env`  
✔ Configurable for production use  

---

## 🎯 **Ideal For**  
- Data Analysts  
- Business Intelligence Teams  
- Research Projects  
- Students & Educators  

---

## 📜 **License**  
This project is licensed under the **MIT License**.  

---
