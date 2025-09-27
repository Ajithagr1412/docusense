📘 DocuSense AI

A RAG-powered chatbot to query your PDFs intelligently

🚀 Overview

DocuSense AI is an AI-powered chatbot that allows users to upload PDF documents and ask natural language questions.
The system uses Retrieval-Augmented Generation (RAG) to extract relevant context from the PDF and generate accurate answers with the help of a Large Language Model (LLM).

This project is designed to showcase practical AI/ML + GenAI integration for real-world applications such as healthcare reports, invoices, contracts, and certificates.

✨ Features

📂 Upload PDF documents.

🔍 Ask natural language questions about the content.

🤖 Uses RAG pipeline (Vector DB + LLM).

🌐 Backend powered by Python + FastAPI.

📱 Optional Flutter app as front-end.

💾 Stores embeddings in vector database for fast retrieval.

🛠️ Tech Stack

Backend: Python, FastAPI, LangChain

LLM: OpenAI GPT / Hugging Face models

RAG: FAISS / Pinecone (vector database)

Frontend: Flutter (optional)

Deployment: Docker, Render/Heroku

📂 Project Structure
DocuSense-AI/
│── backend/
│   ├── app.py              # FastAPI server
│   ├── rag_pipeline.py     # RAG pipeline logic
│   ├── pdf_loader.py       # PDF text extraction
│   ├── requirements.txt
│
│── frontend/
│   ├── lib/                # Flutter app (optional)
│
│── sample_data/
│   ├── sample.pdf
│
│── README.md

⚡ Getting Started
1. Clone the Repo
git clone https://github.com/yourusername/DocuSense-AI.git
cd DocuSense-AI/backend

2. Create Virtual Environment & Install Dependencies
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

pip install -r requirements.txt

3. Run Backend (FastAPI)
uvicorn app:app --reload


Backend runs at: http://127.0.0.1:8000

4. (Optional) Run Flutter Frontend
cd frontend
flutter run

🎯 Use Cases

Healthcare: Query patient reports.

Finance: Extract insights from invoices.

Education: Ask questions from study PDFs.

Legal: Summarize contracts.

📸 Screenshots (Optional)

(Add screenshots of your chatbot / Flutter app here)

📝 Future Enhancements

Support for multiple file types (Word, Excel).

Multi-user support with authentication.

Deploy on cloud (AWS/GCP/Azure).

Add speech-to-text for voice queries.

👩‍💻 Author

Ajitha G.R

💼 Aspiring AI/ML Engineer | Flutter Developer

🌐 LinkedIn
 | GitHub
