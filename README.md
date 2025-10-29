 # Gemini Chat Assistant (Python)

This is a simple command-line chatbot built using **Google’s Gemini API**.  
It mimics a real conversation loop — allowing the user to chat, save history, and get summaries of the session.

 # Features

- Conversational chat powered by **Gemini API**
- Smart word limit: replies contain **15–50 words**
- `save` command — saves the chat history to `conversation.txt`
- `summary` command — summarizes the full conversation
- Error handling and retry logic for API calls
- Simple and easy-to-understand Python structure

## Requirements

Make sure you have **Python 3.10+** installed.

Install dependencies:
```bash
pip install google-generativeai tqdm
