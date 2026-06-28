# Semantic Search with FAISS and Sentence Transformers

A semantic search engine that uses Sentence Transformers and FAISS to retrieve the most relevant document content based on meaning rather than keyword matching. The system supports PDF, DOCX and TXT files.

## Overview

This project extracts text from documents, generates dense vector embeddings, builds a FAISS index, and performs fast semantic similarity search to return the most relevant text chunks.

## Features

* Supports PDF, DOCX, and TXT files
* Automatic text extraction and chunking
* Embedding generation using all-MiniLM-L6-v2
* High-speed semantic search with FAISS
* Ranked search results with similarity scores

## Tech Stack

* Python
* Sentence Transformers
* FAISS
* PyMuPDF
* PyPDF2
* python-docx
* NumPy
* Jupyter Notebook

## Project Structure

```text
main.ipynb    # Complete semantic search implementation
```

## Workflow

1. Extract text from documents.
2. Split text into chunks.
3. Generate embeddings using Sentence Transformers.
4. Build a FAISS vector index.
5. Retrieve the most relevant text based on semantic similarity.

## Installation

```bash
pip install faiss-cpu sentence-transformers python-docx PyMuPDF PyPDF2 numpy
```

## Author

**Kareena Yadav**
