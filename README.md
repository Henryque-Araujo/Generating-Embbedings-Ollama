# 🔠 Generating Embeddings Locally with Ollama

This project demonstrates how to generate text embeddings locally using the `nomic-embed-text` model powered by Ollama.

Through a Python script, it connects to the local Ollama API, sends short text inputs, and returns numerical vectors (embeddings) that semantically represent each sentence.

---

## 🎯 Purpose

* Set up and run Ollama locally
* Generate embeddings using the `nomic-embed-text` model
* Build a Python script to send text inputs and retrieve embeddings
* Display results in a clean and readable format in the terminal
* Store embeddings in memory for future use (e.g., semantic search, classification)

---

## 🧰 Tech Stack

* 🐍 **Python 3.8+**
* 🔗 **Ollama** (local LLM runtime)
* 📦 **requests** (HTTP requests)
* 🧠 **nomic-embed-text** (open-source embedding model)

---

## ⚙️ Requirements

Make sure you have the following installed:

* Python 3.8 or higher
* Ollama installed and running locally
* Git (optional, but recommended)

---

## 🛠️ Setup & Usage

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <your-repo-name>
```

### 2. Install dependencies

```bash
pip install requests
```

### 3. Run the embedding model

```bash
ollama run nomic-embed-text
```

---

## 💡 How It Works

The script sends text data to the local Ollama API endpoint, which processes it using the embedding model and returns a vector representation. These embeddings can be used for tasks like:

* Semantic search
* Text similarity
* Classification
* Clustering

---

## 🚀 Future Improvements

* Persist embeddings in a database (e.g., SQLite, PostgreSQL, or vector DBs)
* Build a semantic search interface
* Integrate with APIs or web applications
* Add batch processing for large datasets
