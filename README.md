# RAG_llma - Retrieval-Augmented Generation Application

## Overview
**RAG_llma** is a **Retrieval-Augmented Generation (RAG)** application designed for **document-based query processing**. It supports **local deployment** and integrates with **PDFs** for contextual retrieval and AI-generated summarization.

The project focuses on building a system that retrieves relevant documents from a vector database and generates responses based on the content, allowing for efficient and contextually accurate document processing.

## Key Features
- **Local Deployment**: The application can be run on local machines without requiring cloud-based services.  
- **Dynamic Vector Database Updates**: Allows real-time updating of vectorized document data to improve retrieval accuracy.  
- **PDF Integration**: Supports PDF document parsing and integrates with the document retrieval pipeline.  
- **AI-Generated Response Quality Evaluation**: Includes functionality to evaluate the relevance and accuracy of AI-generated responses based on the input document.  

## Tech Stack
- **Programming Language:** Python  
- **Libraries & Frameworks:** 
  - **Ollama** for local deployment  
  - **LangChain** for linking language models and pipelines  
  - **Chroma** for vector database (document embedding and retrieval)  
  - **OpenAI API** for summarization and text generation  
  - **Streamlit** for building interactive UI  
  - **PyPDF** for PDF parsing and extraction  

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DocuRAG.git
   cd DocuRAG
