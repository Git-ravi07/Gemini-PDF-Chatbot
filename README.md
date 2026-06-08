# 🤖 Gemini RAG PDF Chatbot

A Retrieval-Augmented Generation (RAG) pipeline built to allow real-time interactive chatting with any PDF document. This project utilizes local sentence-transformers for fast, free semantic search and Google's Gemini-3.5-Flash for advanced reasoning and answering.

## 🚀 Features
- **Local Embeddings:** Uses `all-MiniLM-L6-v2` via HuggingFace, bypassing external API rate limits ($429$ errors).
- **Vector Storage:** Powered by ChromaDB for seamless, lightweight semantic retrieval.
- **Advanced LLM:** Integrated with Google Gemini via LangChain to deliver highly accurate context-aware answers.

## 🛠️ Tech Stack
- Python
- LangChain / LangChain Community
- Google Generative AI (Gemini API)
- ChromaDB
- SentenceTransformers

## 📦 Installation & Setup
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
