# Retrieval-Augmented Generation (RAG) System

## Overview

A document-based RAG system that retrieves relevant information
from a local knowledge base using semantic search and generates
answers using an LLM through the OpenRouter API.

## Architecture

Documents
   ↓
LangChain Text Splitting
   ↓
Sentence Transformers
   ↓
FAISS
   ↓
Semantic Retrieval
   ↓
Retrieved Context
   ↓
OpenRouter LLM
   ↓
Generated Answer

## Technologies

- Python
- LangChain
- Sentence Transformers
- FAISS
- OpenRouter API
- NumPy

## How to Run

1. Install dependencies
2. Add your OpenRouter API key
3. Run the notebook
4. Enter a question
5. Receive an answer with source documents