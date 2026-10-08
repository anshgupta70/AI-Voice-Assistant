# 🤖 AI Voice Assistant

An AI-powered voice assistant built with **Python and LiveKit Agents** that can understand spoken commands and perform useful tasks through an interactive voice interface.

The assistant is designed to work like a personal AI agent, capable of handling conversations and using external tools such as web search, weather information, and email.

## ✨ Features

* 🎙️ **Real-time voice interaction**
* 🤖 AI-powered conversational assistant
* 🌐 Web search capability
* 🌤️ Weather information
* 📧 Send emails using voice commands
* 🧰 Tool/function calling
* 🔊 Voice activity and audio processing
* 🧠 Context-aware conversations
* 🔐 Environment-variable based API configuration

## 🛠️ Tech Stack

* **Python**
* **LiveKit Agents**
* **LiveKit**
* **Google AI / LLM APIs**
* **Python dotenv**
* **Noise Cancellation**
* **Web Search APIs**
* **Weather API**
* **Email integration**

## 📂 Project Structure

```text
AI_Voice_Assistant/
│
├── agent.py
├── tools.py
├── .env
├── requirements.txt
└── README.md
```

> Your actual filenames may differ. Update this section according to your project structure.

## ⚙️ How It Works

The basic workflow is:

```text
User speaks
     ↓
Voice Input
     ↓
LiveKit Agent
     ↓
Speech / AI Processing
     ↓
LLM understands the request
     ↓
Tool selection (if required)
     ↓
Weather / Web Search / Email
     ↓
AI generates response
     ↓
Voice Response
```

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project directory:

```env
LIVEKIT_URL=your_livekit_url
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret

GOOGLE_API_KEY=your_google_api_key
```

Add any other API keys required by your tools.

### 5. Run the assistant

```bash
python agent.py
```

Follow the terminal instructions to connect the voice assistant to your LiveKit session.

## 🧰 Available Tools

### 🌤️ Weather

The assistant can retrieve weather information based on a user's request.

Example:

```text
User: What's the weather today?
Assistant: [Provides current weather information]
```

### 🌐 Web Search

The assistant can search the web when additional information is required.

Example:

```text
User: Search the web for the latest AI news.
Assistant: [Performs a web search and responds]
```

### 📧 Email

The assistant can send emails through voice commands.

Example:

```text
User: Send an email to Rahul saying I'll meet him tomorrow.
Assistant: [Creates and sends the email]
```

## 🔐 Environment Variables

**Never commit your `.env` file to GitHub.**

Add the following to `.gitignore`:

```gitignore
.env
venv/
__pycache__/
*.pyc
```

Your API keys and secrets should always remain private.

## 🔮 Future Improvements

* [ ] Support multiple email accounts
* [ ] Add calendar integration
* [ ] Add task/reminder management
* [ ] Add persistent conversation memory
* [ ] Add a web-based frontend
* [ ] Improve wake-word detection
* [ ] Add more AI tools
* [ ] Improve multilingual voice support
* [ ] Add user authentication
* [ ] Deploy the assistant to the cloud

## 🎯 Learning Outcomes

Through this project, I explored:

* Building AI agents with Python
* Real-time voice-based AI interaction
* LLM integration
* Function/tool calling
* API integration
* Environment variable management
* Audio processing
* Building an end-to-end AI application

## 👨‍💻 Author

**Ansh Gupta**

B.Tech — Artificial Intelligence & Machine Learning
ITM Gwalior

---

⭐ If you find this project interesting, consider giving the repository a star!
