# 🤖 IPage Vision Chatbot

An AI-powered conversational chatbot built using **Flowise**, **Groq LLM**, and **Pinecone Vector Database**, designed to answer questions about *IPage Vision* accurately using Retrieval-Augmented Generation (RAG). The chatbot also supports **voice-based interaction** through **AssemblyAI speech-to-text integration**.

---

## 🚀 Overview

The **IPage Vision Chatbot** is a document-aware AI assistant that provides reliable, context-aware responses strictly based on stored knowledge. It rewrites user queries for better understanding, retrieves relevant documents from a vector database, and generates grounded answers while maintaining conversational memory.

This project demonstrates a real-world implementation of **RAG pipelines**, conversational memory, and multimodal (voice + text) interaction using modern AI tooling.

---

## ✨ Key Features

* 💬 Conversational AI chatbot using Flowise
* 🧠 Retrieval-Augmented Generation (RAG)
* 🔍 Semantic document search with vector embeddings
* 🗂️ Pinecone-backed vector document store
* 🧾 Strict hallucination prevention (answers only from context)
* 🕘 Conversation memory using Buffer Window Memory
* 🎙️ Voice input support via AssemblyAI (speech-to-text)
* 🧩 Modular and scalable chatflow design

---

## 🛠️ Tech Stack

* **Flowise** – Visual AI workflow & chatflow builder
* **Groq LLM (LLaMA 3.1)** – Fast and efficient language model
* **Pinecone** – Vector database for semantic search
* **AssemblyAI** – Speech-to-text for voice-based queries
* **Conversational Retrieval QA Chain** – RAG-based QA pipeline
* **Buffer Window Memory** – Context retention across chats

---

## 🧠 How It Works

1. User asks a question via text or voice input
2. Voice input is transcribed using AssemblyAI
3. The query is rewritten into a standalone question
4. Relevant documents are retrieved from the vector store
5. The AI generates a response strictly from retrieved context
6. Chat history is maintained for conversational continuity
7. If no relevant data is found, a safe fallback response is returned

---

## 📂 Repository Contents

* `chatflow.json` – Flowise chatbot workflow configuration
* `vector-store/` – Document embeddings and vector setup
* `prompts/` – Prompt templates used in the QA chain
* `docs/` – Project documentation and references

---

## 🎥 Demo Video

📌 **Title:** IPage Vision AI Chatbot Demo
⏱️ **Duration:** 7 minutes
▶️ **Link:** [https://youtu.be/SjS55a8MuKw](https://youtu.be/SjS55a8MuKw)

The demo walks through the complete chatbot workflow, including query handling, document retrieval, conversational memory, and voice input support.

---

## 👨‍💻 Author

**Anjan Manohar**

* Built the complete chatbot architecture
* Designed the Flowise chatflow
* Integrated Groq LLM, Pinecone, and AssemblyAI
* Implemented hallucination-safe response logic
* Tested and validated end-to-end functionality

---

## 📌 Use Cases

* Customer support chatbots
* Internal knowledge base assistants
* AI-powered documentation search
* Business information bots

---

## 📜 License

This project is open-source and available for learning, experimentation, and extension.

---

⭐ If you found this project useful, feel free to star the repository and explore further enhancements!
