#Learning-Groq

This repository contains a Streamlit app for **document-based question answering** using **Retrieval-Augmented Generation (RAG)**. The system leverages the LangChain framework, Groq's LLaMA 3.1, and FAISS for efficient document embedding, retrieval, and Q&A generation.

## Features

- **Groq Llama3**: Uses Groq's Llama 3.1 model (8B) as the primary large language model (LLM) for generating answers.
- **FAISS**: Fast and scalable vector store for document embedding and similarity search.
- **LangChain Integration**: Handles document splitting, embeddings, retrieval, and chaining for seamless interactions.
- **PDF Ingestion**: Load research papers from a local directory and generate vector embeddings for querying.
- **Real-Time Response**: Query the loaded documents and get accurate, context-based responses in real-time using Streamlit's interactive UI.


## Usage

1. **Embed Documents**: Click the **"Document Embedding"** button to process and embed the PDF documents.
2. **Ask a Question**: Input your query related to the documents in the text field and get an answer based on the document's content.
3. **View Similar Documents**: Expand the **"Document Similarity Search"** section to see the relevant document snippets.

## Project Structure

- **`app.py`**: Main Streamlit app for user interaction.
- **`research_papers/`**: Directory containing PDF files for document ingestion.
- **`requirements.txt`**: List of dependencies required to run the app.
- **`.env`**: File for storing API keys (not committed for security reasons).

## Technologies Used

- **Groq's Llama3** for question answering.
- **LangChain** for document handling and retrieval chains.
- **FAISS** for vector similarity search.
- **Streamlit** for interactive UI.
- **PyPDFDirectoryLoader** for loading PDFs.


