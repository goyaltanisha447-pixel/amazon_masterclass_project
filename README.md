# amazon_masterclass_project
# 🧠 AI-Powered Product Review RAG Assistant

An intelligent **Retrieval-Augmented Generation (RAG)** application that analyzes product reviews using **Sentence Transformers**, **FAISS**, and **GPT-2**. The system retrieves the most relevant customer reviews through semantic search and generates context-aware responses to user queries.

---

## 🚀 Features

* Semantic search using **Sentence Transformers**
* High-speed similarity search with **FAISS**
* AI-generated responses using **GPT-2**
* Data preprocessing and text cleaning
* Product review analysis and visualization
* Word Cloud generation for review insights
* Review length and rating distribution analysis
* Embedding visualization using **PCA**
* Precision and Recall evaluation for retrieval performance

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Sentence Transformers**
* **FAISS**
* **Transformers (GPT-2)**
* **WordCloud**

---

## 📂 Dataset

The project uses a CSV dataset containing:

* Product Name
* Customer Review
* Product Rating

Example columns:

* `product_name`
* `Review`
* `Rate`

---

## ⚙️ Project Workflow

1. Load and preprocess the product review dataset.
2. Clean review text by removing punctuation and special characters.
3. Perform Exploratory Data Analysis (EDA):

   * Rating Distribution
   * Word Cloud
   * Review Length Distribution
4. Generate sentence embeddings using **all-MiniLM-L6-v2**.
5. Store embeddings in a **FAISS Vector Database**.
6. Perform semantic search based on user queries.
7. Evaluate retrieval using Precision and Recall.
8. Generate AI-powered answers using **GPT-2** with retrieved reviews as context.

---

## 🔍 Sample Queries

* Is the battery life good?
* Fast charging battery
* Good camera phone
* Comfortable headphones
* Energy efficient air conditioner

---

## 📊 Output

The application provides:

* Top relevant customer reviews
* Semantic search results
* AI-generated answers
* PCA visualization of embeddings
* Rating distribution charts
* Word cloud visualization
* Precision and Recall metrics

---

## 📁 Project Structure

```
├── Dataset-SA.csv
├── python.py
├── requirements.txt
└── README.md
```

---

## ▶️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python python.py
```

---

## 🎯 Future Enhancements

* Replace GPT-2 with advanced LLMs such as Llama 3, Mistral, or Gemini.
* Develop an interactive web interface using Gradio or Streamlit.
* Integrate cloud-based vector databases like Pinecone or ChromaDB.
* Support PDF and document-based Retrieval-Augmented Generation.
* Add multilingual semantic search capabilities.

---

## 👩‍💻 Author

**Tanisha Goyal**

B.Tech (AI & ML Enthusiast) | Full Stack Developer | AI & RAG Developer

---

⭐ If you found this project useful, consider giving it a star on GitHub!
