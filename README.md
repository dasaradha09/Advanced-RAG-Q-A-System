# 🧠 RAG Q&A App (Retrieval-Augmented Generation)

This is a Streamlit-based Question Answering (QA) application that allows users to upload or input documents and ask questions based on the content. The app uses **FAISS** for document vector storage, **sentence-transformers** for embeddings, and **Meta-Llama 3 (via Hugging Face)** as the large language model (LLM) to generate answers.

---

## 🚀 Features

- ✅ Upload and process various input types: `PDF`, `DOCX`, `TXT`, `Text`, and `Web URLs`
- ✅ Automatic chunking and embedding of document contents using HuggingFace Transformers
- ✅ Uses `FAISS` for fast and scalable similarity search
- ✅ Powered by `Meta-Llama-3-8B-Instruct` via Hugging Face Inference Endpoints
- ✅ Intuitive web UI with `Streamlit`

---

## 📁 Supported Input Types

- **Link** – Web page (URL) scraped using `WebBaseLoader`
- **PDF** – Upload `.pdf` files
- **DOCX** – Upload `.docx` or `.doc` files
- **TXT** – Upload `.txt` files
- **Text** – Direct text input into a form
