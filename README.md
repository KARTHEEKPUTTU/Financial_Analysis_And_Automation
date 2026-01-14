# Financial Analysis and Automation using LLMs

## Overview
This project implements an end-to-end financial analysis and automation pipeline that combines financial data retrieval, semantic search, and large language models (LLMs) to answer complex questions about publicly traded companies.

The system retrieves company and stock information, converts textual descriptions into vector embeddings, stores them in a vector database, and performs Retrieval-Augmented Generation (RAG) to generate intelligent, context-aware financial insights.

---

## Key Features
- Automated retrieval of company stock information using Yahoo Finance
- Text embedding generation using Hugging Face sentence-transformer models
- Vector storage and semantic search using Pinecone
- Parallel processing for large-scale company data ingestion
- Retrieval-Augmented Generation (RAG) for financial question answering
- LLM-powered responses using Groq-hosted LLaMA models

---

## Tech Stack
- **Python**
- **yFinance** – stock and company data retrieval
- **Hugging Face Sentence Transformers** – text embeddings
- **Pinecone** – vector database for semantic search
- **LangChain** – document handling and vector integration
- **Groq (LLaMA 3.1)** – large language model inference
- **scikit-learn** – cosine similarity calculations
- **Jupyter Notebook**

---

## Workflow
1. Fetch company metadata and business summaries using Yahoo Finance
2. Generate sentence embeddings for company descriptions
3. Store embeddings in a Pinecone vector index
4. Track successful and failed data ingestion
5. Perform semantic similarity search for user queries
6. Augment retrieved context and query an LLM
7. Generate structured, human-readable financial insights

---

## Example Use Case
Users can ask questions such as:
- *"What are some companies that manufacture consumer hardware?"*
- *"Which companies operate in the semiconductor sector?"*

The system retrieves the most relevant company descriptions and generates accurate, context-aware responses using an LLM.

---

## Project Type
- Applied Machine Learning
- Natural Language Processing (NLP)
- Retrieval-Augmented Generation (RAG)
- Financial Data Automation

---

## Notes
- API keys (Pinecone, Groq) are managed securely using environment variables.
- This project focuses on automation and intelligent analysis rather than traditional dashboards.

---

## Author
Kartheek Puttu
