<h1 align="center">Hi, I'm Sidharth K 👋</h1>

<p align="center">
  <b>AI Engineer | GenAI | AI Agents | LLM Applications</b><br>
  I build production-ready Generative AI systems: AI agents, RAG, MCP, and scalable backends that solve real business problems.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sidharth-k-0b9894341/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:sidharthabimanyu242@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/SIDHARTHABIMANYU"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## ⚡ At a Glance

- 🏢 AI Engineer Intern at **Spinacle Technologies**, taking AI systems from architecture to live production
- 🔌 Deployed **MCP servers** (SSE + Streamable HTTP) and a **self-hosted SLM (Qwen 2.5 via Ollama)** on AWS EC2
- 🧠 Integrated **3 LLM providers** (Groq, Gemini, Sarvam AI) into production pipelines
- 🚀 Cut resume screening from **hours to under 30 seconds** per candidate
- 🔍 Flagged **44 anomalies across 870 retail records** with ML-based detection
- 🎓 M.Sc. Applied Data Science, SRMIST (CGPA 8.66)

---

## 🚀 What I Build

🤖 AI Agents & LLM Workflows • 🧠 RAG & Semantic Search • 🔗 LangChain & LangGraph • 🔌 Model Context Protocol (MCP) • 📊 Anomaly Detection & Data Reliability • ⚡ FastAPI & Async Backend Systems • ☁️ AWS & Docker Deployments • 🎙️ Voice AI & OCR Pipelines

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

| Category | Skills |
|---|---|
| **Languages** | Python • SQL |
| **AI / GenAI** | LangChain • LangGraph • RAG • LLMs • Small Language Models (SLMs) • Sentence Transformers • Hugging Face Embeddings • ChromaDB • Pinecone • MCP • Human-in-the-Loop (HITL) • Prompt Engineering • AWS Bedrock • Gemini • Groq • Ollama • Qwen • Sarvam AI |
| **ML & Data** | scikit-learn • pandas • Isolation Forest • Z-score Anomaly Detection |
| **Backend** | FastAPI • Celery • Redis • REST APIs • Webhooks • Async Workflows |
| **Databases** | PostgreSQL • SQLite • Firestore • DynamoDB • ChromaDB • Pinecone |
| **Cloud & DevOps** | AWS EC2 • AWS S3 • AWS Bedrock • AWS Amplify • Docker • Docker Compose • Nginx • PM2 • Git • GitHub |

---

## 💼 Experience

**AI Engineer Intern, Spinacle Technologies** | Apr 2026 – Oct 2026
- Architected **AI Agent workflows using LangGraph and LangChain**, applying stateful multi-turn orchestration for conversational products and sequential pipelines for automated document processing
- Built **RAG pipelines with ChromaDB and Sentence Transformers**, structuring vector-based conversation memory so agents could recall guest history and personalize responses without maintaining external state
- Deployed **dual MCP server transports (SSE + Streamable HTTP)** for real-time bidirectional AI control of production web apps, and hosted **Qwen 2.5:3b locally via Ollama on AWS EC2** behind a PM2-managed Node.js proxy, cutting dependency on external LLM APIs
- Took AI systems from architecture through live production deployment using **Docker, AWS EC2, and Nginx**, hardening webhook-based bots, voice AI pipelines, and hybrid OCR under real usage
- Integrated **3 LLM providers (Groq, Gemini 2.0 Flash, Sarvam AI)** into production pipelines for intent classification, resume parsing, and multilingual voice processing

---

## 🔥 Featured Projects

### 🤖 [TalentFlow AI Recruitment System](https://github.com/SIDHARTHABIMANYU/TalentFlow-AI)
AI-powered recruitment automation with resume parsing, semantic candidate-job matching, OCR, human-in-the-loop approval, and automated email workflows.
- ⚡ Cut resume screening from **hours to under 30 seconds** per candidate
- 🐳 **6-container Docker pipeline** with Celery Beat polling and hybrid OCR (Tesseract + PyPDF2/pdfplumber)
- 🎯 Hybrid matching (keyword + Sentence-Transformer cosine similarity) generating **SHORTLIST / CONSIDER / REJECT** recommendations
- 👤 Telegram inline-approve buttons + React dashboard (Google OAuth, JWT)

`FastAPI` `LangGraph` `Gemini` `PostgreSQL` `ChromaDB` `Celery` `Redis` `Docker` `AWS`

---

### 🛡️ [AI Data Reliability Copilot](https://github.com/SIDHARTHABIMANYU/AI-Data-Reliability-Copilot)
AI copilot that detects data anomalies, investigates pipeline incidents, and recommends fixes, with engineers approving every action.
- 🔍 Flagged **44 anomalies (5.06%) across 870 retail records** (revenue, stock availability, supplier performance) using Isolation Forest + Z-score detection
- 🧭 **LangGraph investigation workflow** combining incident evidence, Pinecone retrieval, and LLMs to produce findings, root causes, and remediation steps
- ✅ **Human-in-the-loop approve/reject flow** with PostgreSQL audit records
- 🔌 **MCP server** exposing read-only pipeline-monitoring and data-quality tools to AI clients

`Python` `FastAPI` `LangGraph` `LangChain` `Pinecone` `Hugging Face` `Gemini` `AWS Bedrock` `AWS S3` `scikit-learn` `pandas` `PostgreSQL` `MCP`

---

### 🏨 [Myve Hotel AI Assistant](https://github.com/SIDHARTHABIMANYU/Hotel-AI)
Conversational hotel assistant that replaces manual front-desk requests with self-serve chat and gives staff live visibility into guest tasks.
- 💬 **LangGraph intent-classification agent** across **WhatsApp and Telegram**, with **ChromaDB RAG memory** and **Sarvam AI** voice transcription/translation
- 📋 **Firebase-backed staff dashboard** for real-time task management
- 📲 **Dynamic QR codes** that launch a pre-filled chat with branch and room data, so guest onboarding takes a single scan

`FastAPI` `LangGraph` `LangChain (Groq)` `Sarvam AI` `ChromaDB` `SQLite` `Firebase Firestore` `Telegram Bot API`

---

### 🎵 [Musicfy AI Platform](https://github.com/SIDHARTHABIMANYU/musicfy-ai-backend)
AI music platform where a small language model runs on my own server and AI clients like Claude can connect through MCP.
- 🧠 Runs **Qwen 2.5 (3B) SLM locally via Ollama on AWS EC2**, reducing dependence on external LLM APIs
- 🔌 **MCP integration** so external AI clients such as Claude can access and control the platform
- 🤝 **Agent-to-agent concert booking workflows**
- 🗄️ **DynamoDB** backend
- ☁️ Cloud deployment with **AWS EC2 and AWS Amplify**

`Ollama` `Qwen (SLM)` `MCP` `DynamoDB` `AWS EC2` `AWS Amplify`

---

### 🩺 [AI Doctor Appointment Booking Agent](https://github.com/SIDHARTHABIMANYU/AI-Doctor-Appointment-Booking-)
Conversational Telegram agent that handles the full appointment lifecycle.
- 📅 Removes manual scheduling by handling booking end to end via **webhooks**
- 🔎 Real-time doctor discovery and slot management by querying **PostgreSQL** during the conversation
- 💬 Cancellations and rescheduling in **natural language**, with no phone coordination

`Python` `FastAPI` `PostgreSQL` `Telegram Bot API` `Webhooks`

---

## 📚 Currently Focused On

Production AI Engineering • AI Agents • RAG Systems • MCP • Backend & System Design • Cloud Deployment

---

## 📫 Connect With Me

- 💼 LinkedIn: [sidharth-k-0b9894341](https://www.linkedin.com/in/sidharth-k-0b9894341/)
- 📧 Email: [sidharthabimanyu242@gmail.com](mailto:sidharthabimanyu242@gmail.com)
- 💻 GitHub: [SIDHARTHABIMANYU](https://github.com/SIDHARTHABIMANYU)

<p align="center"><i>Open to AI Engineer opportunities. Let's build something great. 🚀</i></p>
