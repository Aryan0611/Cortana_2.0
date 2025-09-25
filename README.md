<img width="900" height="900" alt="Image" src="https://github.com/user-attachments/assets/3292d09c-473b-4b7e-ac26-95857c2b9ae9" />
📌 Overview

Cortana 2.0 is a Python-based Virtual Assistant inspired by J.A.R.V.I.S & Microsoft’s Cortana.
It can listen to your commands, process them, and perform a variety of tasks like:

✅ Open applications (Notepad, Calculator, CMD, Camera, Discord)
✅ Search Wikipedia & Google
✅ Play YouTube videos
✅ Fetch latest news & trending movies
✅ Give weather reports
✅ Send WhatsApp messages & Emails
✅ Tell jokes & give random advice
✅ Speak results back to you using Text-to-Speech (pyttsx3)

All this, powered by Speech Recognition + APIs + Automation.

🛠️ Features

🎤 Voice Commands – Speak naturally, Cortana 2.0 will understand.

🔊 Text-to-Speech (TTS) – Talks back to you using pyttsx3 (sapi5).

🌍 Internet Functions – Weather, News, Movies, Jokes, Advice.

💻 System Operations – Open apps directly via commands.

📱 Messaging – WhatsApp messages + Gmail emails.

🔐 Secure API Keys – Handled with .env & decouple.

📂 Project Structure
Cortana-2.0/
│
├── main.py                 # Main assistant loop
├── functions/
│   ├── online_ops.py       # Internet-related operations
│   ├── os_ops.py           # System-related operations
│
├── requirements.txt        # All dependencies
├── .env                    # API keys (ignored in GitHub)
└── README.md               # Project documentation

⚡ Tech Stack

Language: Python 🐍

Libraries:

requests → API calls

wikipedia → Wikipedia summaries

pywhatkit → YouTube, Google, WhatsApp automation

pyttsx3 → Text-to-Speech (offline)

speech_recognition → Speech-to-Text

smtplib & email.message → Emails

decouple → Handle .env for API keys

APIs Used:

IPify
 – Get public IP

NewsAPI
 – Latest news

OpenWeather
 – Weather report

TMDB
 – Trending movies

icanhazdadjoke
 – Random jokes

AdviceSlip
 – Random advice
