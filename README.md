# JARVIS-VOICE-ASSISTANT-SYSTEM
Here is the full text version of the project documentation and setup instructions from the images provided:

JARVIS-Voice-Assistant-System
JARVIS is a Python-based voice assistant that can interact with the user through speech recognition, perform tasks like opening applications, searching on Google or Wikipedia, playing music randomly, telling jokes, and having small talk.

This project uses speech recognition and text-to-speech (TTS) to provide a hands-free assistant experience similar to Iron Man’s JARVIS.

## 🛠 Features
Greet the user according to the time of day (morning, afternoon, evening).

Recognize voice commands using Google Speech Recognition.

Speak responses using pyttsx3.

Time & Date announcements.

Wikipedia search with spoken summary.

Open websites like Google, Facebook, YouTube.

Play random music from a specified folder.

Open system applications: Calculator, Notepad, CMD.

Open Calendar (Google Calendar via browser).

Tell jokes and respond to basic small talk.

Exit gracefully with a voice command.

## 🚀 How to run?
Create a virtual environment:
```bash 
conda create -n jarvis python=3.11 -y 
```

Activate virtual environment: ```bash
conda activate jarvis 
 ```

Install required packages:```bash
 pip install -r requirements.txt
 ```

Run the JARVIS script: python jarvis.py

## 👤 Author
Arithra roy Inspired by Tony Stark's JARVIS.

## 📜 License
This project is open-source and free to use for learning purposes

