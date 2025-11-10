# Multi-Document-Q-A-bot
This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using **FastAPI** and **ChromaDB**.  
It allows users to upload and query their own documents to get **context-aware answers** powered by **GPT** or **Gemini** language models.

---

## 🚀 Features

- 📂 Upload up to **20 PDF or text files** (each up to 1000 pages)
- 🧩 Automatic text chunking and vector embedding generation
- 🧠 Storage and retrieval using **ChromaDB**
- 💬 Intelligent question answering with **GPT** or **Gemini**
- ⚡ Fast and lightweight backend built with **FastAPI**
- 🌐 Ready for deployment via **Uvicorn** or **Ngrok**

---

## 🧠 Tech Stack

### Backend: 
FastAPI

### Database: 
ChromaDB

### Embeddings: 
Sentence Transformers

### Models: 
GPT / Gemini

File Handling: PyPDF2, aiofiles

Deployment: Uvicorn, Ngrok
