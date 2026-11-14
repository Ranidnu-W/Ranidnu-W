# Hi, I'm Deyon Wijewardana

**Aspiring AI/ML Engineer** building retrieval-augmented generation (RAG) systems and agentic AI applications.

I'm a Computer Science student and a Machine Learning Fellow in **Break Through Tech AI Studio** (Fall 2026), where I'm building an AI research assistant for **Zayi**. I like taking an LLM idea all the way from raw data to a tested, measurable system with a usable interface.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-deyon--wijewardana-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deyon-wijewardana)
[![Email](https://img.shields.io/badge/Email-randinu1235%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:randinu1235@gmail.com)

## Break Through Tech AI Studio: Zayi

**Machine Learning Fellow** · Sept 2026 – Dec 2026 · Team of 6 with an industry challenge advisor

**[Agentic Internal Knowledge System for R&D](https://github.com/Break-Through-Tech/Zayi-1B-agentic-internal-knowledge-system-for-r-and-d)**: a RAG assistant that answers questions over 10 ArXiv ML research papers, cites the exact paper and page for every claim, and declines to answer when the papers don't cover the question.

What I built:
- **Data pipeline:** token-aware cleaning and chunking (553 chunks with page-level provenance). I measured that 62% of the earlier word-based chunks exceeded the embedding model's 512-token limit and replaced that approach.
- **Vector search:** a ChromaDB knowledge base (bge-small embeddings) and a LangChain retriever with FlashRank cross-encoder reranking.
- **RAG pipeline:** a LangChain + Gemini answer chain with source-linked citations. 14/16 correct on the first live ground-truth test, with 100% valid citations.
- **Evaluation:** page-level retrieval evaluation on a 40-question ground-truth set. Reranking raised page hit@5 from 78% to 90%.
- **App and tests:** a Gradio chat app with clickable citations that open the source page, plus most of the 144-test pytest suite.

## Tech Stack

**Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**AI / ML:** ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat) ![Hugging Face](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat)

**Tools:** ![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## Other Projects

- **[Nexus](https://github.com/Ranidnu-W/Nexus):** a self-hosted multi-agent AI platform that routes requests to specialized agents for document Q&A, review analysis, and file processing. It runs 9 n8n workflows on a local stack (Ollama with Llama 3 8B, Qdrant, Docling) with a Next.js frontend.
- **[BitHelix](https://github.com/Ranidnu-W/BitHelix):** a reversible pipeline that encodes any file into synthesis-ready DNA sequences, with error correction and GC-content balancing.
- **[AI Model Comparison](https://github.com/Ranidnu-W/04-model-comparison):** an n8n workflow that runs security-alert text through several AI models (sentiment, zero-shot classification, NER, LLM reasoning) and compares the results in Airtable.

## Currently Learning

- Agentic self-correction with LangGraph
- LLM evaluation (retrieval metrics, answer grading)

## GitHub Activity

![GitHub Streak](https://streak-stats.demolab.com?user=Ranidnu-W&hide_border=true)
