# Open-Source-RAG-
This is an Open Source RAG project

This Streamlit app allows users to upload or input content from various sources—URLs, PDFs, Word Docs, text files, or raw text—and ask questions about it using a Retrieval-Augmented Generation (RAG) pipeline.

💬 Input: Upload documents or paste links/text

✂️ Processing: Text is chunked and embedded using all-mpnet-base-v2

🔍 Retrieval: Relevant chunks are retrieved using a FAISS vector store

🧠 Answering: A large language model (via Hugging Face) answers questions based on the retrieved context

📲 UI: All wrapped in an interactive Streamlit interface

Powered by LangChain, FAISS, and Hugging Face, this app makes it easy to build and test document-aware Q&A workflows.
