⚖️ LexAI - Legal Intelligence Platform

LexAI is an AI-powered legal assistant built with Streamlit and Groq AI. It allows lawyers, legal professionals, and researchers to upload legal documents and ask questions about them in natural language.

Features

- 📄 Upload PDF, Word, and Excel documents
- 🤖 AI-powered legal document analysis
- 💬 Interactive chat interface
- 📂 Multiple document support
- 🧠 Context-aware question answering
- ⚡ Fast responses using Groq LLMs
- 📝 Conversation history tracking

Supported File Types

- PDF (.pdf)
- Microsoft Word (.docx)
- Microsoft Excel (.xlsx)

How It Works

1. Upload one or more legal documents.
2. Click Process Documents.
3. LexAI extracts text from the documents.
4. Ask questions in plain English.
5. Receive AI-generated answers based on the uploaded documents.

Technology Stack

- Python
- Streamlit
- Groq API
- Llama 3
- PyPDF2
- python-docx
- openpyxl

Installation

Clone the repository:

git clone https://github.com/ALLISTARK-TECHS/lawyers-assistant-AI.git
cd lawyers-assistant-AI

Install dependencies:

pip install -r requirements.txt

Add your Groq API key:

GROQ_API_KEY = "your-groq-api-key"

Run the application:

streamlit run ogundiranai.py

Project Structure

lawyers-assistant-AI/
│
├── ogundiranai.py
├── README.md
└── requirements.txt

Disclaimer

LexAI is intended for informational and research purposes only. It does not provide legal advice and should not replace consultation with a licensed attorney.

Author

ALLISTARK-TECHS

Building AI solutions for legal professionals.
