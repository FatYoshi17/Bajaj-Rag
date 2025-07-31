# Bajaj-RAG: Retrieval-Augmented Generation for Insurance Document QA

This project implements a Retrieval-Augmented Generation (RAG) pipeline tailored for answering queries related to Bajaj insurance documents using LLMs and vector databases.

## 🧠 Features

- 📄 Upload and index insurance-related PDFs
- 🔍 Use FAISS + Sentence Transformers for document retrieval
- 🤖 Answer user queries using LLMs with retrieved document chunks
- 🛠️ Modular architecture with FastAPI backend
- 📦 HuggingFace + LangChain integration

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/FatYoshi17/Bajaj-Rag.git
   cd Bajaj-Rag

📁 Bajaj-Rag/
├── main.py                # FastAPI app
├── rag_utils.py           # Retrieval and generation logic
├── ingest.py              # Document ingestion and vector indexing
├── faiss_store/           # Stored vector DB
├── data/                  # Sample insurance documents
└── requirements.txt
