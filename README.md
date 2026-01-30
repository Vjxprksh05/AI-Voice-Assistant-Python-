
# Nova – AI Desktop Voice Assistant 🎙️🖥️

Nova is a real-time AI-powered Windows desktop voice assistant built using LiveKit Agents and Google Gemini Realtime API.  
It listens to voice commands, responds naturally, and can open desktop applications like Notepad, Calculator, Word, and Excel.

---

## 🚀 Features

- 🎧 Real-time voice interaction (low latency)
- 🧠 Powered by Google Gemini 1.5 Pro Realtime
- 🖥️ Opens Windows desktop applications via voice
- 😴 Sleep & Wake control using voice commands
- 🔇 Built-in noise cancellation
- 🔐 Secure API key handling with .env

---

## 🛠️ Tech Stack

- Python
- LiveKit Agents
- Google Gemini Realtime API
- Asyncio
- dotenv
- Noise Cancellation (BVC)

---

## 🗂️ Project Structure

```text
.
├── agent.py            # Main application
├── .env                # API keys (not committed)
├── requirements.txt
└── README.md


⸻

⚙️ Setup & Installation

1️⃣ Clone the repository

git clone https://github.com/Vjxprksh05/AI-Voice-Assistant-Python.git
cd AI-Voice-Assistant-Python

2️⃣ Create virtual environment (recommended)

python -m venv venv
source venv/Scripts/activate   # Windows

3️⃣ Install dependencies

pip install -r requirements.txt

4️⃣ Configure environment variables

Create a .env file:

GOOGLE_API_KEY=your_google_api_key_here


⸻

▶️ Run the Application

python agent.py.console

⚠️ This project is Windows-only due to desktop app integrations.

⸻

🗣️ Voice Commands Examples
 • “Open Notepad”
 • “Open Calculator”
 • “Go to sleep”
 • “Nova” → Wake up
 • “Shutdown” → Exit assistant

⸻

🔒 Security Notes
 • .env is ignored via .gitignore
 • API keys are never hardcoded  
