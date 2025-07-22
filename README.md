# 📚 PAI – Student Voice Assistant

An open-source AI-powered assistant for students, teachers & parents, built with Flutter, Node.js, Whisper & ChatGPT.

---

## ✨ Features
✅ Voice commands  
✅ Timetable & homework  
✅ Class codes & quizzes  
✅ Daily/weekly reports  
✅ Works on Android, iOS, web

---

## 🧰 Tech Stack
- Flutter (frontend)
- Node.js & Firebase (backend & DB)
- Whisper (speech-to-text)
- ChatGPT / OpenRouter (natural language)
- pyttsx3 or Google TTS (voice output)

---

## 📦 Project Structure
PAI-Voice-Assistant/
├── backend/              # Node.js API
│   ├── package.json
│   └── src/
│       ├── controllers/
│       ├── routes/
│       └── app.js
├── frontend/             # Flutter app
│   ├── lib/
│   │   ├── screens/
│   │   ├── widgets/
│   │   └── main.dart
│   └── pubspec.yaml
├── voicebot/             # Python voice bot (Whisper + TTS)
│   ├── pai_voicebot.py
│   └── requirements.txt
├── docs/                 # Diagrams, screenshots, API docs
│   └── roadmap.md
├── .gitignore
├── LICENSE
└── README.md


