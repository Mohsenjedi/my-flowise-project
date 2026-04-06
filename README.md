# my-flowise-project
# 🤖 PDF Chatbot with Flowise (RAG Pipeline)

![Flowise](https://img.shields.io/badge/Built%20with-Flowise-blue)
![RAG](https://img.shields.io/badge/Architecture-RAG-green)
![LLM](https://img.shields.io/badge/LLM-Mistral-orange)

---

## 📌 Overview

This project is a **Flowise chatflow** that enables you to chat with any PDF document using AI.

It is built using a **Retrieval-Augmented Generation (RAG)** pipeline, allowing the system to retrieve relevant information from the document and generate accurate, context-aware responses.

---

## 🔗 Chatflow File

👉 Download or use the chatflow here:
**[Open Chatflow JSON](YOUR_LINK_HERE)**

---

## 🧠 Architecture

This system follows a standard RAG pipeline:

1. **PDF Loader**

   * Loads and extracts text from PDF files

2. **Text Splitter**

   * Splits text into smaller chunks for better processing

3. **Embeddings**

   * Generates vector embeddings using Google Gemini

4. **Vector Store**

   * Stores embeddings in an in-memory vector database

5. **Retriever**

   * Finds the most relevant chunks based on user query

6. **LLM (Mistral)**

   * Generates answers using retrieved context

7. **Memory**

   * Maintains conversation history for better responses

---

## 🧱 Tech Stack

* **Flowise**
* **Mistral AI** (Chat Model)
* **Google Generative AI** (Embeddings)
* **In-Memory Vector Store**

---

## ⚙️ Setup & Usage

### 1. Import Chatflow

* Open Flowise
* Click **Import Chatflow**
* Upload the JSON file

### 2. Configure API Keys

Add your credentials:

* Mistral API Key
* Google Generative AI API Key

### 3. Upload PDF

* Provide your PDF file in the PDF node

### 4. Start Chatting

Ask questions about your document 🎉

---

## 🚀 Features

* 📄 Chat with any PDF
* 🧠 Context-aware answers (RAG)
* 💬 Conversational memory
* ⚡ Fast in-memory retrieval
* 🔍 Accurate document-based responses

---

## 🔐 Security Note

⚠️ Never expose your API keys in public repositories.
Use `.env` files and add them to `.gitignore`.

---

## 📂 Project Structure

```
.
├── 1 Chatflow.json
├── README.md
└── images/ (optional)
```

---

## 📈 Use Cases

* Document Q&A
* Research assistant
* Internal knowledge base
* Customer support automation

---

## 👨‍💻 Author

Mohsen jedi

---

## ⭐ Support

If you found this useful, consider giving this repo a star ⭐
