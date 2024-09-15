# MultiPDF Chat App :books:

## Overview

The MultiPDF Chat App is a Python application that allows you to upload multiple PDF documents and chat with the data. You can ask questions about the PDFs using natural language, and the app will provide relevant responses based on the content of the documents.

### Features
- Upload multiple PDF documents
- Chat with the content of the PDFs
- Ask natural language questions
- Receive accurate responses based on PDF content

### How It Works

1. **PDF Loading**: The app reads multiple PDF documents and extracts their text content.
2. **Text Chunking**: The extracted text is divided into smaller chunks for efficient processing.
3. **Language Model**: Utilizes a language model to generate vector representations (embeddings) of the text chunks.
4. **Similarity Matching**: The app compares your question with text chunks and identifies the most semantically similar ones.
5. **Response Generation**: The selected chunks are passed to the language model, which generates a response based on the PDF content.

### Tech Stack

- Python
- Streamlit
- LangChain
- OpenAI Embeddings
- FAISS
- PyPDF2

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/avr-varshan/multipdf-chat-app.git
