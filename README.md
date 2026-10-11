# LangGraph AI Chatbot 🤖

An AI chatbot built using **Streamlit, LangGraph, and Google Gemini** with tool calling, conversation history, and streaming responses.

## Features

- AI chat using Gemini 3.1 Flash Lite
- Web search using DuckDuckGo
- Calculator for arithmetic operations
- Stock price lookup using Alpha Vantage
- Persistent conversation history using SQLite
- Real-time streaming responses

## Tech Stack

Python, Streamlit, LangGraph, LangChain, Google Gemini, DuckDuckGo, SQLite.

## Project Structure

```text
langgraph-chatbot/
├── langgraph_tool_frontend.py
├── langgraph_tool_backend.py
├── requirements.txt
├── .env
└── chatbot.db
```

## Setup

**1. Create a virtual environment**

```bash
python -m venv .venv
```

**2. Activate the environment (Windows)**

```powershell
.venv\Scripts\activate
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Configure environment variables**

Create a `.env` file containing your Google Gemini and LangSmith API keys.

**5. Run the application**

```bash
streamlit run langgraph_tool_frontend.py
```

## How It Works

Streamlit provides the chat interface, while LangGraph manages the conversation workflow, tool execution, and persistent state using SQLite.
