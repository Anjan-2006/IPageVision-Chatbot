# IPage Vision Chatbot

An AI-powered conversational chatbot built using **Flowise**, **Groq LLM**, and **Pinecone Vector Database**, designed to answer questions about *IPage Vision* accurately using Retrieval-Augmented Generation (RAG). The chatbot also supports voice-based interaction through **AssemblyAI speech-to-text integration**.

---

## Overview

The **IPage Vision Chatbot** is a document-aware AI assistant that provides reliable, context-aware responses strictly based on stored knowledge. It rewrites user queries for better understanding, retrieves relevant documents from a vector database, and generates grounded answers while maintaining conversational memory.

This project demonstrates a real-world implementation of Retrieval-Augmented Generation pipelines, conversational memory, and multimodal (voice and text) interaction using modern AI tooling.

---

## Key Features

* Conversational AI chatbot built using Flowise
* Retrieval-Augmented Generation (RAG)
* Semantic document search using vector embeddings
* Pinecone-backed vector document store
* Strict hallucination prevention (answers generated only from retrieved context)
* Conversation memory using Buffer Window Memory
* Voice input support using AssemblyAI (speech-to-text)
* Modular and scalable chatflow architecture

---

## Tech Stack

* **Flowise** – Visual AI workflow and chatflow builder
* **Groq LLM (LLaMA 3.1)** – High-performance language model
* **Pinecone** – Vector database for semantic document retrieval
* **AssemblyAI** – Speech-to-text conversion for voice-based queries
* **Conversational Retrieval QA Chain** – RAG-based question answering pipeline
* **Buffer Window Memory** – Context retention across conversations

---

## How It Works

1. Frequently Asked Questions (FAQ) documents are ingested and embedded into the vector database
2. The user interacts with the chatbot using text or voice input
3. Voice input is transcribed into text using AssemblyAI
4. The query is rewritten into a standalone question by the language model
5. Relevant document chunks are retrieved from the vector database
6. The AI generates a response strictly based on the retrieved context
7. Conversation history is maintained for contextual continuity
8. If no relevant information is found, a safe fallback response is returned

---

## Repository Structure

* `ipagevision Chatflow.json` – Flowise chatflow configuration defining the complete chatbot pipeline
* `IPage_Vision_Frequently_Asked_Questions` – Primary knowledge base used for vector embeddings and retrieval
* `index.html` – Frontend interface for interacting with the chatbot
* `screenshots/` – UI and workflow screenshots
* `README.md` – Project overview and documentation

---

## Demo Video

**Title:** IPage Vision AI Chatbot Demo
**Duration:** 7 minutes
**Link:** [https://youtu.be/SjS55a8MuKw](https://youtu.be/SjS55a8MuKw)

The demo provides an end-to-end walkthrough of the chatbot, covering query handling, vector-based document retrieval, conversational memory, and voice input support.

---

## Author

**Anjan Manohar**

* Designed and implemented the complete chatbot architecture
* Built the Flowise chatflow and retrieval pipeline
* Integrated Groq LLM, Pinecone vector store, and AssemblyAI
* Implemented hallucination-safe response logic
* Tested and validated the system end-to-end

---

## Use Cases

* Customer support chatbots
* Internal knowledge base assistants
* AI-powered documentation search systems
* Business information and FAQ bots

---

## License

This project is open-source and available for learning, experimentation, and extension.

---

If you find this project useful, feel free to star the repository and explore further enhancements.
