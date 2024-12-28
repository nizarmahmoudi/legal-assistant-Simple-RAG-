# legal-assistant-Simple-RAG-
A legal assistant tool for commercial law queries

This project provides a legal assistant tool powered by the Mistral language model. It is specifically designed to answer questions related to commercial laws and regulations with precision and clarity. The system leverages advanced embedding techniques and vector-based indexing to process and retrieve relevant information from input documents.

## Features
- **Legal Expertise**: Tailored for commercial law-related queries.
- **Document Indexing**: Uses advanced embeddings for efficient information retrieval.
- **Customizable Prompts**: Supports French language queries with domain-specific prompts.
- **State-of-the-Art Model**: Implements the Mistral-7B-v0.1 model with quantization for optimized performance.

## Installation
To get started, install the required dependencies:
```bash
pip install pypdf transformers einops accelerate langchain bitsandbytes sentence_transformers llama-index==0.9.39
