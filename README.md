# Gemini-Chatbot

A Streamlit-based AI chatbot built using Google Gemini LLM. Supports interactive chat, conversation history, and secure API handling using Streamlit Secrets.

This is an interactive AI chatbot built using **Google Gemini LLM** and **Streamlit**.  
The chatbot allows users to ask questions and receive intelligent responses in real time.  
The project securely manages API keys using Streamlit Secrets and maintains chat history.

---

##  Features
- Chat with Google Gemini LLM
- Real-time conversational responses
- Maintains chat history
- Secure API key handling using Streamlit Secrets
- Simple and user-friendly UI
- Fast and lightweight
  
---

##  Tech Stack
- **Frontend**: Streamlit
- **Backend**: Python, Google Generative AI
- **LLM**: Gemini 1.5 Pro

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Mansipatel21/Gemini-Chatbot.git
cd Gemini-Chatbot
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. API Key Setup
1️) Create folder for Streamlit secrets
```bash
mkdir -p .streamlit
```

2️) Create secrets.toml file inside the folder
```bash
nano .streamlit/secrets.toml
```

3️) Add your Gemini API key 
```bash
GEMINI_API_KEY = "your_api_key_here"
```

### 4. Run the App
```bash
streamlit run app.py
```
