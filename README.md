# NeuroSupport AI

A customer-support AI assistant using FastAPI, SQLite, and Google Gemini API.

## Features
- **Intent Classification**: Uses Gemini 2.5 Flash to route queries.
- **RAG (Retrieval Augmented Generation)**: Fetches answers from SQLite.
- **Structured Output**: Returns strict JSON responses.

## Setup

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Environment Variables**
   Create a `.env` file:
   ```
   API_KEY=your_gemini_api_key_here
   ```

3. **Run Application**
   ```bash
   python main.py
   ```
   
4. **Access Docs**
   Open http://localhost:8000/docs for Swagger UI.
