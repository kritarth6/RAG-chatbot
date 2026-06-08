RAG Chatbot using LangChain, OpenAI, and FAISS

Overview

This project implements a Retrieval-Augmented Generation (RAG) chatbot capable of answering user questions based on custom PDF documents. The system combines Large Language Models (LLMs) with semantic document retrieval to provide accurate and context-aware responses.

The application uses LangChain for orchestration, OpenAI models for natural language generation, FAISS for vector similarity search, and Streamlit for the user interface.

---

Features

- Upload and process PDF documents
- Automatic text extraction and chunking
- Embedding generation for document indexing
- Semantic similarity search using FAISS
- Context-aware question answering
- Interactive Streamlit interface
- Retrieval-Augmented Generation (RAG) workflow

---

Tech Stack

Frontend

- Streamlit

LLM Framework

- LangChain

Language Model

- OpenAI GPT Models

Vector Database

- FAISS

Data Processing

- PyPDF
- NumPy
- Pandas

Utilities

- Python Dotenv
- Tiktoken

---

Architecture

User Query

↓

Embedding Search

↓

FAISS Vector Database

↓

Relevant Document Retrieval

↓

Prompt Augmentation

↓

OpenAI LLM

↓

Generated Response

---

Workflow

Document Processing

- Upload PDF documents
- Extract text content
- Split text into manageable chunks
- Generate embeddings
- Store embeddings in FAISS index

Question Answering

- User submits a question
- Query embedding is generated
- Similar document chunks are retrieved
- Retrieved context is combined with the query
- OpenAI model generates a contextual response

---

Installation

git clone https://github.com/kritarth6/RAG-chatbot.git

cd RAG-chatbot

pip install -r requirements.txt

Create a ".env" file:

OPENAI_API_KEY=your_api_key_here

Run the application:

streamlit run app.py

---

Applications

- Enterprise Knowledge Management
- Internal Documentation Search
- Customer Support Assistants
- Research Assistants
- Educational Question Answering Systems

---

Skills Demonstrated

- Generative AI
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Vector Databases
- Semantic Search
- LangChain
- OpenAI API
- Prompt Engineering
- Streamlit Development
- NLP Applications

---

Future Improvements

- Multi-document support
- Chat history and memory
- Hybrid search (keyword + semantic)
- Open-source LLM integration
- Cloud deployment
- Advanced document ranking

---

Author

Kritarth Joshi

LinkedIn:
https://www.linkedin.com/in/kritarth-joshi-60493b304

GitHub:
https://github.com/kritarth6