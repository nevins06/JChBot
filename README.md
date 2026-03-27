# 📄 AskDocs — AI PDF Chatbot (RAG)

AskDocs is a document-based chatbot that allows users to upload PDFs and ask questions.
It uses **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware answers.

---

## 🚀 Features

* 📂 Upload PDF documents
* 💬 Ask questions in natural language
* 🧠 Context-aware answers using RAG
* ⚡ Fast responses using Groq LLM
* 🔍 Semantic search with FAISS

---

## 🛠 Tech Stack

* Python
* Streamlit
* LangChain
* FAISS
* HuggingFace Embeddings
* Groq API (LLM)

---

## ⚙️ How it Works

1. PDF is uploaded and text is extracted
2. Text is split into chunks
3. Chunks are converted into embeddings
4. Stored in FAISS vector database
5. User query → similarity search
6. Relevant chunks → sent to LLM
7. Answer generated

---

## ▶️ Run Locally

```bash
git clone https://github.com/nevins06/AskDocs.git
cd AskDocs
pip install -r requirements.txt
streamlit run ChatBot.py
```

---

## 🔐 Environment Variables

Set your Groq API key:

```bash
setx GROQ_API_KEY "your_api_key"
```

---

## 📌 Future Improvements

* Chat history UI
* Multi-PDF support
* Source citations
* Deployment (Streamlit Cloud)

---

## 👨‍💻 Author

Nevin S
