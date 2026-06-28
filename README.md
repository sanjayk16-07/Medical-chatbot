# 🩺 Medical Chatbot

A conversational AI-powered medical chatbot built with Streamlit and Groq's LLM API. This application provides intelligent responses to medical questions using advanced language models.

## Features

✨ **Key Features Implemented:**

- **AI-Powered Medical Assistance** - Uses Groq's LLaMA 3.1 8B model to provide intelligent medical information and guidance
- **Interactive Chat Interface** - Clean, user-friendly web interface built with Streamlit
- **Message History** - Maintains conversation history for context-aware responses
- **Real-time Responses** - Get instant answers to medical questions
- **Medical Theme UI** - Professional interface with medical emoji and styling
- **Session Management** - Automatic session state handling for persistent conversations

## Tech Stack

- **Frontend**: Streamlit - Python library for building data apps and web interfaces
- **AI Model**: Groq API with LLaMA 3.1 8B Instant model
- **Language**: Python

## Requirements

- Python 3.8+
- Streamlit
- Groq Python client

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Chatbot
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up API Key:**
   ```bash
   export GROQ_API_KEY="your-groq-api-key-here"
   ```
   Or on Windows (PowerShell):
   ```powershell
   $env:GROQ_API_KEY="your-groq-api-key-here"
   ```

## Usage

Run the application:
```bash
streamlit run medical_chatbot.py
```

The chatbot will open in your default web browser at `http://localhost:8501`

## How It Works

1. User enters a medical question in the chat input field
2. The question is sent to the Groq API with the LLaMA 3.1 model
3. The model processes the query with medical assistant context
4. Response is displayed in the chat interface
5. Conversation history is maintained for better context

## Project Structure

```
├── medical_chatbot.py      # Main application file
├── requirements.txt         # Python dependencies
└── README.md               # This file
```

## Dependencies

- **streamlit** - Web app framework for Python
- **groq** - Groq API client for LLaMA models

## Security Note

⚠️ Always keep your `GROQ_API_KEY` secure. Never commit it to version control. Use environment variables or `.env` files (with `.gitignore` protection).

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the chatbot.

## License

[Add your license here]

## Author

Created as an AI-powered medical information assistant.

---

**Note**: This chatbot is designed to provide general medical information and should not be used as a substitute for professional medical advice. Always consult with qualified healthcare professionals for medical concerns.
