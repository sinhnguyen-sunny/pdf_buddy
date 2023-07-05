# Langchain Demo - PDF Text Chatbot

This repository contains a pet demo showcasing the use of Langchain, Hugging Face's Embedding & LLM, to build a chatbot for PDF documents. It is customized from ![original repository](https://github.com/alejandro-ao/ask-multiple-pdfs). The chatbot is deployed as a Streamlit web application on Hugging Face Spaces using GitHub Actions.

## Overview

The Langchain Demo allows you to extract text content from PDF documents and interact with them using a chatbot interface. The main steps involved in the process are as follows:

1. **Extract PDF Text Content**: The demo extracts the text content from PDF documents.

2. **Text Chunking and Embedding**: The extracted text is broken down into smaller chunks and processed using a powerful Hugging Face instruction-finetuned text embedding model and saved in a vector database.

3. **Response Generation**: The selected chunks are then passed to a language model provided by Hugging Face. Conversational retrieval by leveraging the LLM for generating responses, the vector store for efficient similarity-based retrieval, and the conversation buffer memory to maintain the context of the conversation history.