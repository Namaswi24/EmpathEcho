# 🎙️ Conversational Emotion Recognizer

An AI-powered assistant that listens to your speech, detects your emotion, and responds with an emotionally appropriate **spoken reply** — mimicking human empathy through voice and tone.



---

## 🧠 Project Objective

To automate emotion-aware conversations using AI by:
- Recognizing speech from the user.
- Detecting the user's **emotional state**.
- Generating and **voicing a response** tailored to that emotion.
- *(Bonus)* Regulating voice tone (pitch, speed) to match the detected emotion.

---

## ✨ Features

- 🎧 Real-time **speech recognition**
- 😃 Emotion classification from text/audio
- 🗣️ Dynamic **response generation**
- 🔊 Emotion-aware **text-to-speech** (TTS)
- 🌐 A simple and responsive **frontend UI**

---

## 🛠️ Tech Stack

| Component         | Tools/Libraries Used                          |
|------------------|-----------------------------------------------|
| Backend (AI Core) | Python, SpeechRecognition, transformers, pyttsx3 |
| Emotion Detection | BERT, custom NLP model (fine-tuned)          |
| TTS               | gTTS / pyttsx3 / Tacotron-2                  |
| Frontend          | HTML, CSS, JavaScript                        |

---

## 📁 Directory Structure
```
Conversational-Emotion-Recognizer/
│
├── app.py # Main backend controller
├── emotion_model.py # Loads/emotion prediction logic
├── stt.py # Speech-to-text logic
├── response_generator.py # Generates replies based on emotion
├── recorded.wav # Captured user audio input
├── temp_user_audio.wav # Preprocessed audio for analysis
├── mock_response.wav # Sample system reply
├── output.json # Emotion prediction output
├── requirements.txt # Python dependencies
│
├── fine_tuned_emotion_model/ # Trained model files
├── pycache/ # Auto-generated Python cache
│
├── frontend/
│ ├── index.html # Frontend layout
│ ├── style.css # Styling
│ └── script.js # Logic to connect with backend
│
└── README.md # Project overview
```
