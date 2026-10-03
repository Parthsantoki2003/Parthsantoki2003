# Hi there, I'm Parth Santoki 👋

<p align="left">
I design and build intelligent backend systems that combine AI, cloud infrastructure, and scalable APIs to solve real-world enterprise problems.
</p>

<p align="left">
My work focuses on Retrieval-Augmented Generation (RAG), multi-agent AI systems, real-time video analytics, and secure cloud-native applications. I enjoy transforming complex workflows into reliable, production-ready software using Python, FastAPI, PostgreSQL, Docker, and modern AI/ML frameworks.
</p>

---

# 🚀 About Me

- 🐍 Python Backend & AI Developer
- 🤖 Specialized in LLM Agents, RAG, and Computer Vision
- ☁️ Cloud & Docker Enthusiast
- 🏗️ Passionate about System Design, Concurrency, and Scalable Architectures
- 📚 Currently exploring high-performance inference and multi-agent AI orchestration

---

# 💻 Tech Stack

### Languages
Python • Java • SQL • JavaScript • HTML • CSS

### Backend & Infrastructure
FastAPI • REST APIs • WebSockets • WebRTC • Redis • SQLModel • SQLAlchemy • JWT • RBAC

### AI, ML & LLMs
LangChain • LangGraph • DSPy • PyTorch • YOLOv8 • OpenCV • CUDA • Hugging Face • Qdrant • RedisVL

### Database, Cloud & DevOps
PostgreSQL • Docker • Google Cloud Platform (GCP) • Oracle Cloud (OCI) • Vercel 

---

# ⭐ Featured Projects

## 📹 Sentinel – AI Video Analytics & Surveillance Platform
### High-Performance Real-Time Computer Vision System

A full-stack, AI-driven video analytics platform capable of ingesting and processing 30 concurrent live camera streams using WebRTC and RTSP, originally conceived for a statewide multi-department CCTV integration.

### Highlights
- Engineered a multi-threaded inference pipeline separating video capture from AI processing, utilizing **YOLOv8** on **CUDA** to achieve **15ms latency** without dropping frames.
- Designed an OCR ensemble (FastPlateOCR, RapidOCR) with automated API fallback (Gemini/Groq), utilizing cross-frame validation algorithms to eliminate false positives.
- Optimized cloud costs and bandwidth by implementing an edge-based image sharpness filter, reducing unnecessary API calls by 90%.
- Integrated **Redis** for sub-millisecond watchlist lookups and real-time Server-Sent Events (SSE).

**Tech:** Python • FastAPI • React • WebRTC • YOLOv8 • PyTorch • CUDA • PostgreSQL • Redis

---

## 🤖 DocuChat Pro
### Enterprise AI Document Intelligence Platform

DocuChat Pro transforms uploaded documents into an intelligent conversational knowledge base through a highly optimized Retrieval-Augmented Generation (RAG) pipeline. 

### Highlights
- High-performance RAG combining dense vector search and sparse lexical querying with RRF and Cross-Encoder re-ranking.
- Integrated **RedisVL** for semantic caching to optimize retrieval speed and query response times.
- Implemented real-time observability and asynchronous evaluation pipelines using **Langfuse** and the **Ragas** framework to track metrics like Faithfulness and Context Precision.

**Tech:** FastAPI • Qdrant • BM25 • RedisVL • Langfuse • Ragas • PostgreSQL • Docker

---

## 🧠 AI Research Assistant
### Multi-Agent Research Automation Platform

An autonomous research platform that orchestrates multiple AI agents to plan research strategies, retrieve information, analyze evidence, validate findings, and generate structured research reports with minimal human intervention.

### Highlights
- Stateful multi-agent orchestration built with **LangGraph** utilizing a central Supervisor Node.
- Designed a Human-In-The-Loop (HITL) approval process using execution interrupts to review structured outputs before finalizing responses.
- Built custom tool integration nodes (Tavily Web Search, PDF Reader, File Writer) with real-time tracing via Langfuse.

**Tech:** LangGraph • FastAPI • React • Llama 3.3 • SQLite • Tavily API

---

## 🖥️ IT Support AI Agent
### Enterprise AI Knowledge Assistant

An AI-powered enterprise support assistant designed to automate internal IT helpdesk operations using organization-specific knowledge, deployed on Google Cloud Platform.

### Highlights
- Prompt optimization and programmatic response refinement using **DSPy**, significantly reducing LLM hallucination rates.
- Parsed and indexed 500+ pages of text into a hybrid search system to retrieve exact quotes and specific data points quickly.
- Secured application routes using JWT authentication, bcrypt hashing, and granular multi-tier RBAC.

**Tech:** Python • FastAPI • DSPy • Qdrant • PostgreSQL • GCP • Docker

🔗 **Live Demo:** https://it-support-ai-agent.vercel.app/

---

## 📄 DocMind AI
### Multi-Tenant Document Management System

A multi-tenant document management platform that allows users to upload files and query them using an AI assistant, with integrated monetization.

### Highlights
- Implemented API rate-limiting middleware and subscription usage caps linked directly to **Stripe billing tiers**.
- Added Langfuse integration to track LLM response times, monitor token usage, and log query errors.
- Containerized microservices using Docker to separate the API server, background ingestion workers, and vector search operations.

**Tech:** FastAPI • PostgreSQL • SQLModel • Stripe API • Langfuse • Qdrant • Docker

---

## 🏢 IT Infrastructure Management System (ITIMS)
### Enterprise IT Operations Platform

A centralized platform designed to streamline enterprise IT operations by integrating asset lifecycle management, helpdesk services, employee onboarding, audit logging, and operational reporting.

### Highlights
- Enterprise asset management with lifecycle, warranty, assignment, and maintenance tracking.
- Secure FastAPI backend with JWT authentication, RBAC, and scalable REST APIs.

**Tech:** FastAPI • PostgreSQL • JWT • SQLModel • Docker

---

# 📫 Let's Connect

🌐 **Portfolio:** https://santokiparth.dev  
📧 **Email:** parthsantoki5834@gmail.com  
🔗 **LinkedIn:** [https://www.linkedin.com/in/parth-santoki-6584a7332/](#) 

---

> *"I enjoy designing backend systems that combine scalable architectures, intelligent AI workflows, and secure cloud-native applications to solve real-world problems."*
