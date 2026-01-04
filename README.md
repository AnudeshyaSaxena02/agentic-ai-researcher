# Agentic AI Researcher

A **Goal-Driven Autonomous AI System** powered by **LangGraph**, **ReAct Agent Architecture**, and **Google Gemini (Gemini 2.5 Pro)** for deep, multi-step scientific research workflows.  
This agent can **search academic papers**, **read PDFs**, **reason about research**, and **generate LaTeX research papers**, including PDF rendering — all autonomously.

---

## 🚀 Project Overview

Traditional LLM systems generate responses in a single turn. This project builds an **agentic AI** with:

- ✅ Autonomous planning and action loops
- ✅ Tool selection and usage (arXiv search, PDF reading, LaTeX generation)
- ✅ Memory across steps using LangGraph
- ✅ Multi-step, goal-oriented reasoning
- ✅ LaTeX → PDF rendering for research papers

This is more than a chatbot — it’s an **intelligent AI researcher**.

---

## 🧠 Key Features

| Feature | Description |
|---------|-------------|
| 🎯 ReAct Agent | Reason + Act loop for autonomous decision making |
| 🔍 Tool Orchestration | Tools for arXiv search, PDF reading, and PDF rendering |
| 📚 Research Workflow | Topic discussion → paper discovery → reading → ideation → writing |
| 📄 LaTeX PDF Output | Generates properly formatted research papers |

---

## 📦 Tools Included

1. **arxiv_search** — Search and retrieve research papers from arXiv  
2. **read_pdf** — Download and extract text from PDF documents  
3. **render_latex_pdf** — Compile LaTeX content into a high-quality PDF  
4. **LangGraph** — Agent graph execution with memory and state

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| Large LLM | Google Gemini 2.5 Pro (via `langchain_google_genai`) |
| Agent Framework | LangGraph (ReAct and StateGraph) |
| PDF Tools | PyPDF2, Tectonic (for LaTeX compilation) |
| Vector DB | FAISS (for future RAG augmentations) |
| Language | Python |

---

## 📁 Repo Structure

agentic-ai-researcher/
├── arxiv_tool.py
├── frontend.py
├── read_pdf.py
├── write_pdf.py
├── pyproject.toml
├── README.md
└── .gitignore
