# 🎙️ Voice Assistant with Wikipedia & Web Access

A simple **Python-based voice assistant** that responds to user commands using **Google Text-to-Speech (gTTS)** and provides Wikipedia summaries or opens websites like YouTube and Google.

---

## 📌 Features

- ✅ Text-to-Speech using **gTTS**
- ✅ Wikipedia search & summary reading
- ✅ Opens popular websites (YouTube, Google)
- ✅ Simple command-line interface
- ✅ Voice responses for user interaction

---

## 📂 Files Included

- `main.py` — Main Python script for the voice assistant logic  
- `out.wav` — Temporary output file generated for speech (auto-created)  
- `README.md` — Project documentation

---

## 🛠️ Requirements

Install the required libraries using pip:

```bash
pip install gTTS wikipedia
---
## ▶️ How It Works

The assistant waits for user input.

If command contains:

- `"wikipedia"`: It fetches a summary and reads it aloud.
- `"open youtube"` or `"open google"`: Opens the website in your browser.
- `"exit"`: Ends the program.
- If the command isn't recognized, it replies with a default response.

---

## 🔉 Example Interaction

Welcome to the Voice Assistant!
Type your command: wikipedia python programming
User says: wikipedia python programming

[Voice] Searching Wikipedia...
[Voice] Here is what I found on Wikipedia:
[Voice] Python is an interpreted high-level general-purpose programming language...

---

## 🧠 Technologies Used

- [gTTS](https://pypi.org/project/gTTS/) – Google Text-to-Speech  
- [Wikipedia](https://pypi.org/project/wikipedia/) – Python wrapper for Wikipedia API  
- IPython & JavaScript (to open browser tabs)

---

## 🚀 Run the Project

```bash
python main.py
