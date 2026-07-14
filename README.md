# ChatPDF using Google Gemini (RAG)

## Overview

ChatPDF is an AI-powered document question-answering application that enables users to upload one or more PDF files and interact with them through natural language queries. The application uses a Retrieval-Augmented Generation (RAG) pipeline to retrieve relevant information from uploaded documents and generate context-aware responses using Google Gemini.

-----

## Features

- Upload and process multiple PDF documents
- Extract and chunk PDF text automatically
- Semantic search using vector embeddings
- Retrieval-Augmented Generation (RAG)
- Context-aware question answering
- Local vector storage using FAISS
- Secure API key management using environment variables

-----

## Tech Stack

- **Python** – Programming language
- **Streamlit** – Web application
- **LangChain** – RAG workflow
- **Google Gemini 3.1 Flash Lite** – Response generation
- **Gemini Embedding Model** – Text embeddings
- **FAISS** – Local vector store
- **PyPDF2** – PDF text extraction
- **python-dotenv** – Environment variable management

-----

## System Workflow


PDF Documents
      │
      ▼
Text Extraction
      │
      ▼
Text Chunking
      │
      ▼
Gemini Embeddings
      │
      ▼
FAISS Vector Store
      │
User Question
      │
      ▼
Similarity Search
      │
      ▼
Relevant Context
      │
      ▼
Gemini 3.1 Flash Lite
      │
      ▼
Generated Response

-----


## Challenges Faced

- Selecting compatible Gemini models and embedding models with the latest API.
- Managing API quota limitations during development and testing.
- Building an efficient Retrieval-Augmented Generation (RAG) pipeline for document-based question answering.
- Securing sensitive API credentials using `.env` and `.gitignore`.
