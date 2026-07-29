# 🚀 KnowledgePilot AI

> An enterprise-grade AI-powered document intelligence platform that enables semantic document search and contextual question answering using Retrieval-Augmented Generation (RAG).

KnowledgePilot AI allows users to upload PDF documents, build a searchable knowledge base using vector embeddings, and interact with their documents through natural language conversations powered by Large Language Models (LLMs).

---

## ✨ Overview

KnowledgePilot AI combines modern backend engineering with Generative AI to deliver accurate, context-aware answers from enterprise documents. Instead of relying solely on an LLM's pre-trained knowledge, the application retrieves relevant document context using semantic search before generating responses, significantly improving answer quality and reducing hallucinations.

---

## 🚀 Key Features

- 📄 Upload one or multiple PDF documents
- 🤖 AI-powered conversational document assistant
- 🔍 Semantic document search using vector embeddings
- 🧠 Retrieval-Augmented Generation (RAG)
- 💬 Context-aware responses using OpenAI
- ⚡ High-performance FastAPI backend
- 📚 Automatic document chunking & embedding generation
- 🗂️ ChromaDB vector database integration
- 🔐 Secure environment-based API key management
- 🐳 Dockerized deployment
- 📡 RESTful API architecture
- 📝 Interactive Swagger API documentation

---

## 🏗️ System Architecture

```text
                 PDF Documents
                       │
                       ▼
              Text Extraction Layer
                       │
                       ▼
               Document Chunking
                       │
                       ▼
            Embedding Generation
                       │
                       ▼
                 ChromaDB Storage
                       │
                       ▼
             Semantic Similarity Search
                       │
                       ▼
             Relevant Context Retrieval
                       │
                       ▼
               OpenAI Large Language Model
                       │
                       ▼
              AI Generated Response
```

---

## 🛠️ Technology Stack

### Backend

- FastAPI
- Python

### AI / LLM

- OpenAI API
- LangChain
- Retrieval-Augmented Generation (RAG)

### Vector Database

- ChromaDB

### Data Processing

- PyPDF
- Text Chunking
- Embeddings

### DevOps

- Docker
- Git

---

## 📂 Project Structure

```text
KnowledgePilot-AI
│
├── app
│   ├── api
│   ├── services
│   ├── database
│   ├── prompts
│   ├── utils
│   ├── models
│   ├── core
│   └── main.py
│
├── documents
├── chroma_db
├── static
├── templates
├── requirements.txt
├── Dockerfile
├── .env.example
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/KnowledgePilot-AI.git
```

Move into the project

```bash
cd KnowledgePilot-AI
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate it

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file

```env
OPENAI_API_KEY=your_api_key
```

---

## ▶️ Running the Application

```bash
uvicorn app.main:app --reload
```

Application will be available at

```
http://localhost:8000
```

Swagger Documentation

```
http://localhost:8000/docs
```

---

## 📡 REST API

| Method | Endpoint | Description |
|----------|---------------------------|---------------------------|
| POST | /knowledge/upload | Upload PDF documents |
| POST | /knowledge/ask | Ask questions |
| GET | /health | Health Check |

---

## 💡 Use Cases

- Enterprise Knowledge Management
- AI-powered Document Assistant
- Research Paper Search
- Internal Company Documentation
- Technical Documentation Q&A
- Educational Learning Assistant

---

## 🚀 Future Enhancements

- User Authentication
- Conversation History
- Multi-user Support
- Hybrid Search
- Streaming Responses
- Redis Caching
- Azure OpenAI Integration
- Local LLM Support
- Role-Based Access Control

---

## 🎯 Skills Demonstrated

- Backend Development
- REST API Design
- FastAPI
- Large Language Models (LLMs)
- Prompt Engineering
- Retrieval-Augmented Generation (RAG)
- LangChain
- Vector Databases
- ChromaDB
- Semantic Search
- Docker
- Git
- API Integration

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork the repository, open issues, or submit pull requests to improve the project.

---

## 📜 License

This project is released under the MIT License.

---

## 👨‍💻 Author

**Aryan Kush**

Computer Science Graduate | Backend Engineer | AI Enthusiast

GitHub: https://github.com/<your-username>
