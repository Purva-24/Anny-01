# 🤖 ANNY – Personal AI Assistant

A lightweight, terminal-based AI chat assistant inspired by Iron Man's JARVIS, built in Python and powered by the OpenAI API. Talk to it naturally, ask questions, or use it as a quick command-line companion for everyday tasks.

> ⚠️ **Note:** This is a starting template. Update the sections marked for customization to match your exact implementation (file names, library list, features, etc.).

## ✨ Features

- Natural language conversation powered by OpenAI's GPT models
- Simple command-line interface — no extra setup beyond Python
- Maintains conversation context/history during a session
- Easy to extend with new commands or "skills"
- Configurable via environment variables (no hard-coded API keys)

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **AI Engine:** OpenAI API (`openai` Python library)
- **Other libraries used:** *(update this list with what you actually used)*
  - `python-dotenv` – for managing environment variables
  - `requests` – for any custom API calls
  - `colorama` – for colored terminal output *(optional)*

## 📋 Prerequisites

Before running this project, make sure you have:

- Python 3.8 or higher installed
- An [OpenAI API key](https://platform.openai.com/api-keys)
- pip (Python package manager)

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/jarvis-ai-assistant.git
   cd jarvis-ai-assistant
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🔑 Configuration

1. Create a `.env` file in the root directory.
2. Add your OpenAI API key to it:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
3. Never commit your `.env` file — make sure it's listed in `.gitignore`.

## ▶️ Usage

Run the assistant from your terminal:

```bash
python main.py
```

Example interaction:

```
You: Hi Anny, what's the weather like on Mars?
Jarvis: Mars has an average temperature of about -63°C, with a thin
        CO2-rich atmosphere...
```


## 📁 Project Structure

```
Anny - AI Assistant/
├── main.py              # Entry point of the application
├── requirements.txt     # Project dependencies
├── .env                 # API keys (not committed)
├── .gitignore
└── README.md
```

*(Update this structure to reflect your actual file layout.)*

## 🗺️ Roadmap

- [ ] Add voice input/output (speech-to-text & text-to-speech)
- [ ] Add a simple GUI
- [ ] Support custom commands (e.g., open apps, set reminders)
- [ ] Save conversation history to a file/database


## 🙏 Acknowledgements

- Inspired by JARVIS from the Marvel Cinematic Universe
- Built using [OpenAI's API](https://platform.openai.com/)
