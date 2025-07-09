# 🤖 Jarvis - Voice-Controlled AI Assistant in Python

Welcome to **Jarvis**, your own personal AI assistant built using Python. Inspired by Iron Man’s iconic J.A.R.V.I.S., this project was a fun and functional dive into the world of speech recognition, automation, and voice response systems.

> “Jarvis, start the assistant.”  
> ✔️ Already on it, sir.

---

## 🚀 Features

- 🎤 Listens to your voice commands via microphone  
- 📚 Searches and speaks Wikipedia summaries  
- 🌐 Opens websites like YouTube, Google, Stack Overflow  
- 🎵 Plays music from a local directory  
- 🕒 Tells the current time  
- 💌 Can send emails (SMTP config needed)  
- 💻 Opens git VS Code or any specified application  
- 🧠 Greets you based on the time of day  
- 🛑 Listens for "stop", "exit", or "quit" to go offline gracefully

---

## 🛠️ Tech Stack

- **Python 3**
- **Libraries Used**:
  - `pyttsx3` – text-to-speech
  - `speechRecognition` – for mic input
  - `wikipedia` – for fetching info
  - `webbrowser`, `datetime`, `os`, `smtplib` – core Python modules

---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/jarvis.git
   cd jarvis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the assistant**
   ```bash
   python jarvis.py
   ```

4. **Try commands like**:
   - "Open YouTube"
   - "What’s the time"
   - "Wikipedia Elon Musk"
   - "Stop"

---

## 📁 Project Structure

```
jarvis/
├── jarvis.py              # Main script
├── requirements.txt       # Dependencies
├── README.md              # This file
└── .gitignore             # Git exclusions
```

---

## 👀 Demo

> You can imagine Jarvis saying:  
> _“Good Evening, Sir. I am Jarvis. How may I help you?”_

🎧 From there, the assistant listens and executes your command.

---

## 🧠 What I Learned

- Handling real-time speech input
- Integrating multiple Python libraries into one flow
- Automating tasks with voice
- Building voice interaction logic (and dealing with *"say that again please..."*)

---

## 📌 Note

- Ensure your microphone is working.
- Modify paths for music folder and VS Code according to your system.
- To enable email functionality, setup less secure app access for your Gmail (or use OAuth for production).

---

## ✨ Made with curiosity, code, and a pinch of chaos.

---
