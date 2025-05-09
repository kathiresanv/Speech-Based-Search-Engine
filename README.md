## 🗣️ Speech-Based Search Engine

This Python project enables users to perform Google searches using voice commands. It combines speech recognition and text-to-speech to create a hands-free, interactive search assistant.

### 🚀 Features

* 🎤 Voice input using microphone
* 🔊 Voice feedback using text-to-speech
* 🌐 Performs web searches on Google automatically
* 🧠 Simple and efficient codebase using popular libraries

---

### 🧰 Technologies Used

* `speech_recognition` – for converting voice to text
* `pyttsx3` – for converting text to speech
* `webbrowser` – to open search results in a browser

---

### 📁 File Structure

```
speech-based-search-engine/
├── speech based search engine.py
└── README.md
```

---

### ✅ Requirements

Install the necessary libraries using:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> Note: You may need to install `pyaudio` via system packages on some platforms (e.g., using `brew` on macOS or `apt` on Ubuntu).

---

### ▶️ How to Run

1. Connect a working microphone.
2. Run the script:

```bash
python "speech based search engine.py"
```

3. Speak your search query when prompted.
4. The script will recognize your speech, speak back the query, and open Google search results in your default browser.

---

### 📝 Notes

* Make sure your microphone is set up and accessible.
* An active internet connection is required for speech recognition.
* The script uses Google's free speech recognition API.

---

### 📌 To Do

* [ ] Add support for multiple search engines
* [ ] Add GUI using Tkinter or PyQt
* [ ] Improve noise handling and error detection

---

