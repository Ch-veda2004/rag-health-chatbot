# 🏥 RAG Health Chatbot
AI-powered medical assistant using Retrieval Augmented Generation

## Built With
- LangChain + ChromaDB (RAG pipeline)
- Groq LLM (Llama 3.1)
- SentenceTransformers (embeddings)
- Gradio (UI)

## How It Works
1. Medical knowledge stored as vector embeddings in ChromaDB
2. User question matched via similarity search
3. Top 3 relevant chunks retrieved
4. LLM generates grounded answer from context
