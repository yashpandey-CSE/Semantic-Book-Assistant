# 📚 Semantic Book Assistant

An AI-powered system that helps users **discover, understand, and explore books using semantic search and natural language processing (NLP)**.

Instead of simple keyword matching, this assistant understands the **meaning behind user queries** to recommend relevant books intelligently.

---

## 🚀 Features

* 🔍 Semantic book search (based on meaning, not keywords)
* 📖 Smart book recommendations
* 🧠 NLP-powered understanding of user queries
* ⚡ Fast similarity search using embeddings
* 🎯 Clean and interactive interface
* 📊 Data-driven recommendations

---

## 🧠 Tech Stack

* **Python**
* **Pandas / NumPy**
* **Scikit-learn / NLP tools**
* **Sentence Transformers / Embeddings**
* **Streamlit (UI)** *(if used)*
* **Vector Database (for semantic search)**

---

## 📂 Project Structure

```bash
Semantic-Book-Assistant/
│
├── app.py
├── main.py
├── requirements.txt
├── README.md
│
├── data/
│   ├── books.csv
│
├── models/
│   ├── embeddings.pkl
│
├── utils/
│   ├── preprocessing.py
│   ├── recommender.py
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yashpandey-CSE/Semantic-Book-Assistant.git
cd Semantic-Book-Assistant

python -m venv .venv
.venv\Scripts\activate   # Windows

pip install -r requirements.txt
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

OR (if CLI-based):

```bash
python main.py
```

---

## 🔄 How It Works

```text
User Query (Natural Language)
        ↓
Text Preprocessing
        ↓
Convert into Embeddings (Vector Representation)
        ↓
Similarity Search (Cosine Similarity)
        ↓
Top Relevant Books Recommended
```

👉 Semantic systems use embeddings to compare meaning instead of exact words, giving more accurate recommendations

---

## 💡 Example

Input:
👉 "A book about self-growth and motivation"

Output:
👉 Atomic Habits
👉 The Power of Now
👉 Deep Work

---

## 📊 ML Concepts Used

* Semantic Search
* Text Embeddings
* Cosine Similarity
* NLP Preprocessing

---

## 🎯 Use Cases

* 📚 Book recommendation systems
* 🎓 Learning NLP concepts
* 🧠 AI-powered search engines
* 📖 Personalized reading assistants

---

## ⚠️ Requirements

* Python 3.8+
* Basic ML/NLP libraries

---

## 📌 Future Improvements

* Add RAG-based Q&A on books
* Integrate with Google Books / APIs
* Add book summaries & reviews
* Deploy on cloud (Streamlit Cloud)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve 🚀

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
