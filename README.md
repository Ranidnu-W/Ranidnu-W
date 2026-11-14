# Hi, I'm Deyon Wijewardana

**Aspiring AI/ML Engineer** building retrieval-augmented generation (RAG) pipelines and agentic AI systems.

I'm a Computer Science & Engineering student at **NYU Tandon** (expected 2028) and a Machine Learning Fellow in **Break Through Tech AI Studio**. I like taking an LLM idea all the way from raw data to a tested, measurable system with a usable interface.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-deyon--wijewardana-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deyon-wijewardana)
[![Email](https://img.shields.io/badge/Email-randinu1235%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:randinu1235@gmail.com)

## What I Work On

- RAG pipelines: document ingestion, chunking, embeddings, vector search, reranking, and retrieval evaluation
- Agentic systems: multi-agent workflows, MCP tool integrations, mixture-of-experts routing, and agent memory
- Real-time voice agents with WebSockets/Socket.IO and the OpenAI Realtime API
- LLM evaluation and tracing with Braintrust

## Experience

### Break Through Tech AI Studio: Zayi
**Machine Learning Fellow** · Sept 2026 – Dec 2026 · Team of 6 with an industry challenge advisor

**[Agentic Internal Knowledge System for R&D](https://github.com/Break-Through-Tech/Zayi-1B-agentic-internal-knowledge-system-for-r-and-d)**: a RAG assistant that answers questions over 10 ArXiv ML research papers, cites the exact paper and page for every claim, and declines to answer when the papers don't cover the question.

- **Data pipeline:** token-aware cleaning and chunking (553 chunks with page-level provenance). I measured that 62% of the earlier word-based chunks exceeded the embedding model's 512-token limit and replaced that approach.
- **Vector search:** a ChromaDB knowledge base (bge-small embeddings) and a LangChain retriever with FlashRank cross-encoder reranking.
- **RAG pipeline:** a LangChain + Gemini answer chain with source-linked citations. 14/16 correct on the first live ground-truth test, with 100% valid citations.
- **Evaluation:** page-level retrieval evaluation on a 40-question ground-truth set. Reranking raised page hit@5 from 78% to 90%.
- **App and tests:** a Gradio chat app with clickable citations that open the source page, plus most of the 144-test pytest suite.

## Research

**[BitHelix](https://github.com/Ranidnu-W/BitHelix)** · Q-STEM Summer Undergraduate Research Program, Queens College · Summer 2025

A full-stack system that encodes any digital file into synthesizable DNA sequences and decodes it back, using Reed-Solomon error correction and GC-content balancing. I presented the work at the Queens College Undergraduate Research Symposium.
Built with Python, FastAPI, NumPy, pandas, and a TypeScript frontend.

## Projects

| Project | What it is | Stack |
|---|---|---|
| **[Nexus](https://github.com/Ranidnu-W/Nexus)** | Self-hosted multi-agent AI platform: 9 n8n workflows, intent-based routing, and local GPU inference. 96.8% success rate across 186 logged agent interactions, with no paid APIs. | Next.js, TypeScript, n8n, Ollama (Llama 3 8B), Qdrant, Docling, Airtable |
| **[AI Model Comparison](https://github.com/Ranidnu-W/04-model-comparison)** | Runs security-alert text through several AI models (sentiment, zero-shot classification, NER, LLM reasoning) and compares the results. | n8n, multiple AI models, Airtable |
| **[Vibe Warriors](https://github.com/Ranidnu-W/vibe-warriors)** | Registration and participant-management app for the Vibe Battle coding tournament. | Next.js, React, Prisma (SQLite), Tailwind, Framer Motion |
| **[Game Programming](https://github.com/Ranidnu-W/CS3113-Projects)** | 2D games for NYU CS-UY 3113: a scene, Pong, and Lunar Lander. | C++, raylib |

I've also built **AtlasRAG** (self-hosted PDF RAG: Docling, n8n, Qdrant, Ollama, Docker Compose, PostgreSQL, Nginx) and **ReviewRAG** (review Q&A: LangChain, Chroma, Ollama).

## Tech Stack

**Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white) ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-663399?style=flat&logo=css&logoColor=white)

**AI / ML:** ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![Hugging Face](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-555555?style=flat&logo=ollama&logoColor=white) ![Docling](https://img.shields.io/badge/Docling-5A4FCF?style=flat) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**LLMs & Agents:** ![Claude](https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat) ![Mastra](https://img.shields.io/badge/Mastra-555555?style=flat) ![MCP](https://img.shields.io/badge/MCP-555555?style=flat&logo=modelcontextprotocol&logoColor=white) ![Braintrust](https://img.shields.io/badge/Braintrust_evals-555555?style=flat) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)

**Data & Vector DBs:** ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat&logo=airtable&logoColor=white)

**Web & Backend:** ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-555555?style=flat&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-087EA4?style=flat&logo=react&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-555555?style=flat&logo=socketdotio&logoColor=white) ![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![JavaFX](https://img.shields.io/badge/JavaFX-ED8B00?style=flat&logo=openjdk&logoColor=white)

**Tools & Infra:** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-555555?style=flat&logo=linux&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![Doppler](https://img.shields.io/badge/Doppler-555555?style=flat) ![raylib](https://img.shields.io/badge/raylib-555555?style=flat&logo=raylib&logoColor=white)

## Achievements & Learning

- Windsurf AI Hackathon: 4th place (Sept 2025)
- Break Through Tech AI Program, Cornell Tech
- Currently learning: agentic self-correction with LangGraph and LLM evaluation

## GitHub Activity

![GitHub Streak](https://streak-stats.demolab.com?user=Ranidnu-W&hide_border=true)
