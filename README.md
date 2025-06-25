# 📚 Automated Research Assistant

This project is an end-to-end research automation tool that extracts academic articles from Google Scholar, summarizes them using a local LLM, and compiles the results into a structured Word document. It combines browser automation, language model-driven summarization, and workflow orchestration using LangGraph.

---

## 🚀 Features

- 🔍 Parses user prompts to extract concise academic search queries  
- 🌐 Uses Selenium to scrape research papers from Google Scholar  
- 🤖 Summarizes articles with a local Mistral language model via Ollama  
- 📝 Generates a professional Word document with all summaries  
- 🧠 Built on top of LangGraph for modular, stateful workflow control

---

## 🛠️ Technologies Used

- **LangGraph** – Workflow orchestration framework
- **Selenium** – Browser automation for scraping
- **Mistral (via Ollama)** – Local LLM for summarization and query parsing
- **python-docx** – Word document generation
- **Requests** – API communication with local LLM server
- **Python 3.10+**

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/research-assistant.git
   cd research-assistant
