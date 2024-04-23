
---

# Q&A Bot with LangChain using Streamlit

## Overview
This application is a Q&A Bot implemented using Streamlit, leveraging LangChain for document retrieval and language modeling tasks. Users can upload PDF files and ask questions related to the content of the PDF. The bot utilizes pre-trained language and embedding models provided by LangChain to provide accurate answers to user queries.

## Features
- Upload PDF files to the application.
- Select different embedding and language models provided by LangChain.
- Ask questions related to the uploaded PDF content.
- Receive answers based on the content of the PDF, powered by LangChain.

## Installation
1. Clone the repository.
2. Install the required dependencies by running:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Run the application by executing the following command:
   ```
   streamlit run app.py
   ```
2. Once the application is running, upload a PDF file using the file uploader.
3. Select the embedding and language models from the sidebar options.
4. Click the "Submit" button to upload the PDF and generate embeddings.
5. Ask a question in the provided text input field.
6. Click the "Answer" button to receive an answer based on the uploaded PDF content, powered by LangChain.

## LangChain Integration
This application integrates with LangChain, a library providing tools and models for natural language processing tasks. LangChain offers pre-trained embeddings, language models, and document retrieval mechanisms, enhancing the capabilities of the Q&A Bot.

## Dependencies
- streamlit
- langchain
- transformers
- torch
- pdfplumber (for PDF parsing)
- other dependencies as required by LangChain and your specific setup

## Notes
- The application caches resources across multiple sessions for improved performance.
- Different embedding and language models can be selected to customize the behavior of the Q&A bot, with options provided by LangChain.

---
