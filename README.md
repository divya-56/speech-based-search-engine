# speech-based-search-engine

---

# 🗣️ Speech-Based Search Engine

This Python script allows you to perform Google searches using your voice. It leverages speech recognition and text-to-speech technologies to provide a hands-free web search experience.

---

## 🔧 Features

* 🎙️ Listens to your voice using a microphone.
* 🧠 Converts speech to text using Google's Speech Recognition API.
* 🔍 Automatically searches your query on Google.
* 🗣️ Provides voice feedback using text-to-speech.

---

## 📦 Requirements

Install the following dependencies:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> **Note for Windows users:** If you encounter issues installing `pyaudio`, try:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## ▶️ How to Run

1. Make sure your microphone is connected and working.
2. Run the script:

```bash
python "speech based search engine.py"
```

3. When prompted, speak your search query.
4. The script will open the results in your default web browser.

---

## 🧠 How It Works

* Initializes a text-to-speech engine using `pyttsx3`.
* Uses `speech_recognition` to capture audio from the microphone.
* Converts the audio to text using Google's speech recognition API.
* Builds a Google search URL from the recognized query.
* Opens the URL in the default web browser.
* Uses speech synthesis to confirm the action to the user.

---

## 📁 File Overview

**`speech based search engine.py`**

```python
# Uses speech recognition and TTS to perform a Google search.
```

Functions:

* `speak(text)` – Speaks the given text.
* `take_command()` – Listens to and recognizes speech input.
* `search_web(query)` – Opens a browser with Google search results for the query.

---

## ⚠️ Troubleshooting

* If the microphone isn’t working, check your OS input settings.
* If recognition fails, ensure you have a stable internet connection.
* Background noise can affect recognition accuracy.

---

## 💡 Tip

Speak clearly and slowly to improve accuracy of recognition.

---
