# RAG System: Smart PDF Question-Answering

This RAG system is a **smart question-answering system** that allows users to interact with PDF documents **conversationally**. Instead of manually searching through pages, you can simply ask questions and get relevant answers instantly.

It uses a **Retrieval-Augmented Generation (RAG)** pipeline, which combines semantic search with a language model to provide **accurate and context-aware responses**.

---


You can also see the Jupyter Notebook directly on Colab:
Open Notebook in Colab https://colab.research.google.com/drive/1XXGkpQzn9pY4xJMQFQyip9-7yqdNZV6o#scrollTo=8lV7vijkYYA7



## 🔍 What This Project Does

- Reads and processes PDF files  
- Breaks down large text into smaller meaningful chunks  
- Converts text into embeddings for semantic understanding  
- Finds the most relevant information based on user queries  
- Generates human-like answers using a transformer model  

---

## ⚙️ Workflow

### 1. PDF Processing
Extracts text from the document and cleans it for further use.

### 2. Text Chunking
Splits large content into smaller parts for better retrieval.

### 3. Embedding Generation
Each chunk is converted into **vector form** using embedding models.

### 4. Similarity Search
The system compares the **query with stored embeddings** to find relevant context.

### 5. Answer Generation
A language model generates the **final response** using retrieved data.

---

## 🧰 Technologies Used

- Python  
- PyTorch  
- Hugging Face Transformers  
- Sentence Transformers  
- Cosine Similarity (for vector search and embeddings)  

---

## 📦 Setup Instructions

```bash
git clone https://github.com/sbhujel07/RAG_Human_nutrition_fromScratch.git
cd RAG_Human_nutrition_fromScratch
pip install -r requirements.txt