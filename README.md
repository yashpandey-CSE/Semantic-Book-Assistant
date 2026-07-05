# 📚 RAG-Based AI Book Assistant

An intelligent **Retrieval-Augmented Generation (RAG)** application that enables users to upload books, research papers, notes, or text documents and ask natural language questions about their content. The application processes uploaded documents, generates semantic embeddings using **Mistral AI Embeddings**, stores them in **ChromaDB**, retrieves the most relevant information, and produces accurate, context-aware responses using a **Mistral AI Large Language Model (LLM)**.

This project demonstrates the complete Retrieval-Augmented Generation workflow, including document loading, preprocessing, vector database creation, semantic retrieval, and AI-powered question answering.

---

# 🚀 Features

* 📄 Upload PDF and text documents
* 📚 Analyze books, notes, and research papers
* 🤖 AI-powered document question answering
* 🧠 Retrieval-Augmented Generation (RAG)
* 🔍 Semantic search using vector embeddings
* 📦 Persistent Chroma Vector Database
* ⚡ Fast and context-aware responses
* 📖 Multiple retrieval strategies for improved accuracy
* 💬 Interactive document understanding

---

# 🛠️ Tech Stack

| Technology                        | Purpose              |
| --------------------------------- | -------------------- |
| Python                            | Programming Language |
| LangChain                         | RAG Framework        |
| Mistral AI                        | Large Language Model |
| Mistral AI Embeddings             | Semantic Embeddings  |
| ChromaDB                          | Vector Database      |
| PDF/Text Loaders                  | Document Processing  |
| Recursive Character Text Splitter | Text Chunking        |

---

# 📂 Project Structure

```text
RAG-Book-Assistant/
│
├── chroma_db/
│   └── chroma.sqlite3
│
├── document loaders/
│   ├── deeplearning.pdf
│   ├── GRU.pdf
│   ├── notes.txt
│   ├── page.py
│   ├── pdf.py
│   └── test.py
│
├── retrievers/
│   ├── arixv.py
│   ├── mmr.py
│   └── multiquery.py
│
├── vector store/
│   └── DB.py
│
├── create_database.py
├── main.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Project Workflow

1. Upload a PDF or text document.
2. Extract text using document loaders.
3. Split the document into manageable chunks.
4. Generate semantic embeddings using **Mistral AI Embeddings**.
5. Store embeddings in **ChromaDB**.
6. Ask questions related to the uploaded document.
7. Retrieve the most relevant document chunks.
8. Generate accurate answers using the **Mistral AI LLM**.

---

# 🔍 Retrieval Strategies

This project implements multiple retrieval methods to improve response quality:

* Standard Similarity Search
* Maximum Marginal Relevance (MMR)
* MultiQuery Retrieval
* ArXiv Retrieval (for academic resources)

These techniques improve the relevance, diversity, and accuracy of retrieved information before it is passed to the language model.

---

# ▶️ Installation

## Clone the Repository

```bash
git clone https://github.com/<your-username>/RAG-Book-Assistant.git
cd RAG-Book-Assistant
```

## Create a Virtual Environment

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

Create the vector database:

```bash
python create_database.py
```

Start the application:

```bash
python main.py
```

---

# 🎯 Applications

* AI Book Assistant
* Research Paper Analysis
* Document Question Answering
* Knowledge Base Chatbot
* Enterprise Document Search
* Academic Research Assistant
* Personal Knowledge Management
* Intelligent PDF Assistant

---

# 🔮 Future Improvements

* Streamlit-based web interface
* Multi-document conversations
* Conversation memory
* OCR support for scanned PDFs
* Source citations in responses
* Hybrid retrieval (keyword + semantic search)
* Support for DOCX, PPTX, CSV, and Markdown files
* Cloud deployment

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

* Retrieval-Augmented Generation (RAG)
* Large Language Models (LLMs)
* Vector Databases
* Semantic Search
* Document Processing
* Embedding Models
* Prompt Engineering
* Information Retrieval
* LangChain
* AI Application Development

---

# 👨‍💻 Author

**Yash Pandey**

If you found this project useful, consider giving it a ⭐ on GitHub.
