# RAG-WORKSHOP
End-to-end RAG (Retrieval-Augmented Generation) workshop demonstrating how to build a local AI assistant using LangChain, ChromaDB, and Ollama. Includes setup instructions, environment configuration, and practical notebook examples for document-based question answering.

This repository contains a complete Retrieval-Augmented Generation (RAG) workshop designed to help you build and run a local LLM-powered assistant using LangChain, ChromaDB, and Ollama.

HOW TO RUN:
Follow the instructions from the SETUP.HTML file

RAG_Workshop/
├── data/                    # PDF documents for RAG demos
├── rag_env/                 # Python virtual environment
├── RAG_Demo-venv.ipynb      # Main workshop notebook
├── test_rag_setup.py        # Environment verification script (optional)
└── SetUp.html               # Original workshop setup guide

MY RAG SYSTEM
TOPIC: Used lecture PDFs of my NPTEL course on E-Business

WHAT I CHANGED:
Documents: Contains PDF regarding contents E-Business
Chunking: chunk size: 400, overlap: 50
Retrieval: similarity, k = 5

Test Question
What are the types of business information systems?




