# 📚 RAGBot – AI Powered PDF Question Answering System

RAGBot is an AI-powered Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask questions in natural language. It integrates LangChain, Groq LLM, OpenAI Embeddings, Vector Database, and Streamlit UI to provide intelligent document-based answers.

---

# 🚀 Features

- 📄 Upload multiple PDF documents
- 🤖 Ask questions in natural language
- 🔍 Retrieval-Augmented Generation (RAG)
- 🧠 Context-aware AI responses
- ⚡ Powered by Groq LLM for fast inference
- 💬 Chat-based UI using Streamlit
- 🗂️ Semantic search with vector embeddings
- 🔄 Session-based conversation memory

---

# 🛠️ Tech Stack

- Python
- LangChain
- LangGraph
- Groq LLM
- OpenAI Embeddings
- Streamlit
- Vector Store
- RAG Architecture

---

# 📂 Project Structure

```bash
project/
│── doc_files/
│── rag_agent.py
│── requirements.txt
│── .env
│── venv/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ragbot.git
cd ragbot
```

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

## 3️⃣ Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
```

---

# ▶️ Run the Application

```bash
streamlit run rag_agent.py
```

---

# 💡 Example Questions

You can interact with the bot like:

- "Summarize this document"
- "What are the main topics discussed?"
- "Explain chapter 2"
- "Find information about AI"
- "Give key points from the uploaded PDF"

---

# 🧠 How It Works

- Uses LangChain document loaders to read PDFs
- Splits documents into smaller chunks
- Generates embeddings using OpenAI Embeddings
- Stores vectors in a vector database
- Retrieves relevant document chunks using similarity search
- Sends retrieved context to Groq LLM
- Returns intelligent responses in Streamlit chat UI

---

# 🔄 RAG Workflow

```text
PDF Upload
     ↓
Document Loading
     ↓
Text Chunking
     ↓
Embedding Generation
     ↓
Vector Storage
     ↓
Similarity Search
     ↓
Groq LLM Response
```

---

# 🔥 Future Improvements

- ✅ Persistent vector database
- 🌐 Multi-document support
- 📊 Source citation support
- ☁️ Cloud deployment
- 🗣️ Voice-based interaction
- 📱 Mobile responsive UI

---

# 🤝 Contributing

Feel free to fork this repository and submit pull requests!

---

# 📜 License

This project is open-source.

---

# 👨‍💻 Author

**Ravi Bhamniya**

---

# ⭐ Support

If you like this project, don’t forget to star the repository ⭐
