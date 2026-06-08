🤖 RAG Chatbot using LangChain, OpenAI, and FAISS

A Retrieval-Augmented Generation (RAG) chatbot that enables users to interact with custom PDF documents using natural language. The application combines Large Language Models (LLMs) with semantic document retrieval to provide context-aware and accurate responses.

---

🚀 Features

- PDF document upload and processing
- Automatic text extraction and chunking
- Embedding generation for document indexing
- Semantic search using FAISS vector database
- Context-aware question answering
- Interactive Streamlit web interface
- Retrieval-Augmented Generation (RAG) architecture

---

🛠️ Tech Stack

Frontend

- Streamlit

AI Framework

- LangChain

Large Language Model

- OpenAI GPT Models

Vector Database

- FAISS

Data Processing

- PyPDF
- NumPy
- Pandas

Utilities

- Tiktoken
- Python Dotenv

---

📂 Project Structure

RAG-chatbot/
│
├── app.py
├── requirements.txt
├── .env
├── data/
├── vectorstore/
└── README.md

---

⚙️ Architecture

User Query
     │
     ▼
Generate Query Embedding
     │
     ▼
FAISS Vector Search
     │
     ▼
Retrieve Relevant Chunks
     │
     ▼
Prompt Augmentation
     │
     ▼
OpenAI LLM
     │
     ▼
Generated Response

---

🔄 Workflow

Document Processing

1. Upload PDF documents
2. Extract text from PDFs
3. Split text into smaller chunks
4. Generate embeddings
5. Store embeddings in FAISS vector database

Question Answering

1. User asks a question
2. Query embedding is generated
3. Similar document chunks are retrieved
4. Retrieved context is appended to the prompt
5. OpenAI model generates a context-aware response

---

📦 Installation

Clone the repository:

git clone https://github.com/kritarth6/RAG-chatbot.git
cd RAG-chatbot

Install dependencies:

pip install -r requirements.txt

Create a ".env" file:

OPENAI_API_KEY=your_api_key_here

Run the application:

streamlit run app.py

---

🎯 Applications

- Enterprise Knowledge Base Assistant
- Internal Documentation Search
- Customer Support Chatbot
- Research Assistant
- Educational Question Answering
- Document Intelligence Systems

---

🧠 Skills Demonstrated

- Generative AI
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- LangChain
- OpenAI API Integration
- Vector Databases
- FAISS
- Semantic Search
- Prompt Engineering
- Streamlit Development
- Natural Language Processing (NLP)

---

🔮 Future Enhancements

- Multi-document support
- Conversation memory
- Hybrid search (semantic + keyword)
- Open-source LLM integration
- Cloud deployment
- Advanced document ranking

---

👨‍💻 Author

Kritarth Joshi

LinkedIn:
https://www.linkedin.com/in/kritarth-joshi-60493b304

GitHub:
https://github.com/kritarth6

---

⭐ If you found this project useful, consider giving it a star!