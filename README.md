# Hi, I'm Muhammad Hamza — AI Engineer (Agentic AI • RAG • LLM Orchestration)

I build **agentic AI systems** and **RAG** pipelines for real-world products. My focus areas:
- **Multi-agent orchestration** (supervisor–worker, dynamic planning, tool calling)
- **Retrieval-Augmented Generation (RAG)** with vector databases
- **LLM apps** with **LangChain / LangGraph / LlamaIndex** and **OpenAI function calling**
- **Applied AI integration**: FastAPI backends, AWS deployments, voice (STT/TTS), and CV pipelines

---

## Core Skills 
- **Languages:** Python (primary), TypeScript/Node.js (basic)
- **Agent Frameworks:** LangChain, **LangGraph**, LlamaIndex, AI Agent SDK, OpenAI Function Calling  
- **Agentic Patterns:** Tool usage, dynamic planning, **goal decomposition & task chaining**, memory persistence & context injection, **self-healing workflows**, failover strategies, agent state monitoring
- **RAG & Vectors:** Pinecone, Chromadb, FAISS, embeddings on S3
- **Backend :** **FastAPI**, Flask, Docker, AWS (EC2, S3, SageMaker), Git
- **Event-driven :** Kafka/RabbitMQ style orchestration, webhooks, queues
- **ML/CV:** PyTorch, TensorFlow, YOLOv8, Detectron2, Mask R-CNN

---

## Highlight Projects (What I actually built)

### 1) Research Pal — Advanced **RAG** Assistant  
**Live:** https://researchpal.co/  
**Stack:** LangChain, Pinecone/Chromadb, OpenAI, FastAPI, AWS  
**What it does:** Semantic retrieval over academic papers with **context injection**, multi-turn reasoning, and structured outputs.  
**Agent Design:** Retrieval tool + reasoning agent; hybrid search (semantic + keyword) to reduce hallucination.  
**Challenges & Fixes:** Scaling retrieval → optimized chunking/embeddings; ambiguity → intent routing + disambiguation prompts.

---

### 2) Doojo AI — **Voice AI** Chatbot with **Multi-Agent Orchestration**  
**Stack:** LangGraph, AI Agent SDK, OpenAI, STT/TTS, FastAPI  
**What it does:** Supervisor–worker agents handle availability checks, booking flows, and tool-calling.  
**Agent Design:**  
- **Supervisor**: interprets goals, decomposes tasks  
- **Workers**: retrieval, scheduling, API calls  
- **Memory**: persistent convo state + vector recall  
**Challenges & Fixes:** Tool failures → retry/backoff + fallback routes; long sessions → session memory trimming & relevant context refresh.

---

### 3) Drake AI — Enterprise Conversational System (**RAG + Memory**)  
**Stack:** LangChain, LlamaIndex, OpenAI, FastAPI, AWS  
**What it does:** Knowledge-grounded chat with **persistent memory** and **task chaining** for enterprise FAQs and workflows.  
**Highlights:** Structured tool outputs, context windows managed via memory stores, failover prompts for edge cases.

---

### 4) Anna — Computer Vision Platform (Annotation → Training → Inference)  
**Stack:** YOLOv8, Detectron2, Mask R-CNN, FastAPI, Docker  
**What it does:** End-to-end platform to annotate datasets and train CV models with clean deployment workflows.  

---

## Architecture Patterns I Use
- **Toolformer-style tool usage** with **OpenAI function calling**  
- **RAG pipelines** with query planning, re-ranking, and **context injection**  
- **Self-healing workflows**: retries, fallbacks, guardrails
- **State & Memory**: vector recall + short-term convo buffers  
- **Event-driven**: background tasks/queues, webhook triggers, Kafka/RabbitMQ patterns 

---

## Code & Repos 
> I’m actively organizing code for public view. In the meantime:
-  **GitHub:** https://github.com/Hamzajani153  
-  **Research Pal (live):** https://researchpal.co/  
- `agentic-voice-bot` — LangGraph multi-agent + TTS/STT + tool-calling
- `enterprise-rag-starter` — LangChain + FAISS/Pinecone + FastAPI
- `agent-tools-kit` — function-calling tool wrappers (search/db/llm)

---

## Tech I Work With

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0B3B61?logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-222222?logo=graphql&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-1B6AC6?logo=semantic-web&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-0A6A90?logo=pine64&logoColor=white)
![Chromadb](https://img.shields.io/badge/FAISS-20232A?logo=databricks&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)

---

## Contact
- **Email:** descent.hamza153@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/muhammad-hamza-401777253  
- **Location:** Rawalpindi, Pakistan  
- **Portfolio :** https://hamzajani153.github.io/Hamzajani153/
