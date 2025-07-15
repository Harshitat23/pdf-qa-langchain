# 📄 PDF-Powered QA System using Embeddings + LangChain

A Question-Answering (QA) system that allows you to upload any PDF document and then ask natural language questions about its content.
Built with LangChain, embeddings, and vector stores to provide accurate and context-aware answers.

🚀 Features

🔹Upload any PDF and parse its content

🔹Generate embeddings for chunks of the PDF

🔹Store embeddings in a vector database for efficient retrieval
 
🔹Ask questions in natural language and get precise answers

🔹Powered by LangChain for document retrieval and LLM integration

🔹Simple and modular codebase for easy customization

🏗️ Tech Stack

-> Python 3.10+

-> LangChain

-> FAISS / Chroma (Vector Store)

-> OpenAI or HuggingFace LLMs

-> PyPDF2 / pdfplumber for PDF text extraction

📖 How It Works

1️⃣ Extract PDF text → Split into smaller chunks

2️⃣ Generate embeddings → Store in vector database

3️⃣ Ask question → LangChain retrieves relevant chunks

4️⃣ LLM answers → Combines retrieved chunks into a response
