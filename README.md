# AI Document Chatbot (RAG Pipeline)

## Overview

AI Document Chatbot is a Retrieval-Augmented Generation (RAG) system built using n8n, Supabase Vector Database, OpenAI Embeddings, and Gemini/OpenRouter models.

The system automatically ingests documents from Google Drive, converts them into vector embeddings, stores them in a vector database, and enables users to chat with their knowledge base using natural language.

---

## Features

- Automated Google Drive document ingestion
- Vector embedding generation
- Supabase Vector Database storage
- Conversational AI interface
- Semantic search and retrieval
- Automatic document update handling
- Automatic document deletion synchronization
- Retrieval-Augmented Generation (RAG)

---

## Architecture

Google Drive

↓

Document Processing

↓

Embedding Generation

↓

Supabase Vector Database

↓

Retriever

↓

LLM (Gemini/OpenRouter)

↓

AI Chat Interface

---

## Tech Stack

- n8n
- Supabase
- OpenAI Embeddings
- Gemini/OpenAI API
- OpenRouter
- Google Drive

---

## Workflow Capabilities

### Document Upload

- Detects new documents uploaded to Google Drive
- Downloads and processes files automatically
- Generates vector embeddings
- Stores vectors in Supabase

### Document Updates

- Detects document modifications
- Removes outdated vectors
- Re-indexes updated content

### Document Deletion

- Detects deleted documents
- Removes corresponding vectors from database

### AI Chat

- Searches relevant chunks
- Retrieves context
- Generates accurate answers using RAG

---

## Learning Outcomes

- Retrieval-Augmented Generation
- Vector Databases
- Embedding Models
- Semantic Search
- AI Workflow Automation
- Knowledge Base Construction

---

## Future Improvements

- Multi-user support
- Document version tracking
- Hybrid search
- Citation support
- Agentic retrieval workflows

---

## Author

Manthan Lathiya

GitHub: https://github.com/Manthan-Lathiya
LinkedIn: https://www.linkedin.com/in/manthan-lathiya/
