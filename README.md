# 🚀 AI Log Analyzer

An intelligent log analysis system that automates the detection, classification, and root cause analysis of system logs, crash dumps, and ETW traces using AI.

---

## 📌 Overview

AI Log Analyzer is a full-stack application designed to help developers and system engineers quickly diagnose issues from large volumes of logs.  
It integrates AI-based pattern recognition with system-level debugging tools to provide accurate insights and actionable fixes.

---

## ✨ Features

- 🔍 Automated Log Analysis (TXT, Event Viewer Logs)
- 🧠 AI-Based Error Classification (using LLM)
- 📊 Timeline Reconstruction of Events
- 📁 Crash Dump Analysis using WinDbg
- ⚡ ETW (Event Tracing for Windows) Analysis
- 🔗 Root Cause Correlation across multiple files
- 💬 Interactive AI Chat for debugging help
- 📄 Auto-generated HTML Reports

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **AI Integration:** Ollama (LLaMA 3.1:8b)
- **Frontend:** HTML, CSS
- **Database:** SQLite
- **Tools:** WinDbg, Tracerpt
- **Libraries:** Flask-CORS, Requests, Threading, JSON

---

## 📂 Project Structure
AI_LOG_ANALYZER/
│
├── backend/
│ ├── Aiunified.py
│ ├── chathistory.db
│ └── templates/
│ └── Aiunified.html
│
├── analysis_reports/
├── uploaded_pdbs/
└── README.md


⚙️ Installation & Setup
pip install flask flask-cors requests
python backend/Aiunified.py
outside install ollama(ai model) and install model llama3.1:8b model


**How It Works**
Upload logs, dump files, or ETL traces
System parses and groups patterns
AI model analyzes logs and identifies:
Subsystem
Root cause
Fix suggestions
Generates:
Analysis reports
Timeline reconstruction
Final root cause analysis
