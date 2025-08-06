# ByteBot 🤖 – Multilingual Voice-based Insurance Chatbot

**ByteBot** is a smart, multilingual, voice-powered insurance assistant built for the **InsureBot Quest 2025 Hackathon**, hosted by **ValuEnable** and backed by **Rainmatter (Zerodha)**.

It helps users interact with their life insurance policy using natural language voice queries in **5 Indian languages** — offering instant, accurate, and human-like responses.

---

## 🌐 Supported Languages
- English 🇬🇧
- Hindi 🇮🇳
- Telugu 🇮🇳
- Tamil 🇮🇳
- Kannada 🇮🇳

---

## 🎯 Key Features
- 🎙️ Voice input (speech-to-text using Google Speech API)
- 💬 Real-time voice output (text-to-speech using gTTS)
- 🌐 Auto-detect and respond in user’s language
- 🧠 NLP-based question matching using spaCy and FuzzyWuzzy
- ⚡ Lightning-fast responses with intelligent caching
- 📚 FAQ-driven knowledge base using simple `faq_data.json`

---

## 🛠️ Tech Stack

| Layer      | Tools/Frameworks |
|------------|------------------|
| Frontend   | HTML, CSS, JavaScript (Voice UI) |
| Backend    | Python + Flask |
| Voice I/O  | gTTS, Google SpeechRecognition |
| NLP & ML   | spaCy (`en_core_web_md`), FuzzyWuzzy |
| Data       | JSON knowledge base |
| Translation & Language Detection | `googletrans` |

---

## 🚀 How to Run Locally

### 1. Clone this repo
```bash
git clone https://github.com/Sahithi544/ByteBot.git
cd ByteBot
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
python -m spacy download en_core_web_md
```

### 3. Run the chatbot
```bash
python app.py
```

Then open `http://localhost:5000` in your browser to interact with ByteBot.

---

## 📂 Folder Structure

```
ByteBot/
│
├── app.py               # Flask web server
├── chatbot.py           # Core logic for speech + NLP + response
├── faq_data.json        # Custom knowledge base
├── requirements.txt     # Python dependencies
├── templates/
│   └── chatbot.html     # Voice chat UI
└── static/              # (Optional) For future CSS/JS
```

---

## 🎥 Demo Video

📽️ Watch ByteBot in action:  
https://drive.google.com/file/d/1Rye0W6LpoH55MwbHedRY29a0lhe0-hhu/view?usp=drive_link

---

## 💡 Example Use Cases

- “When is my policy due date?”  
- “How much premium did I pay?”  
- “What is the fund value?”  
- “How to change my mobile number?”  
- “What is ValuEnable?”  
- “Policy ko surrender kaise karein?” (Hindi)

---

## 👥 Team ByteBot

Built with ❤️ by **Team ByteBot**  
For the **InsureBot Quest 2025 – Round 2 Submission**  
Organized by **ValuEnable Pvt. Ltd.**

---

## 📃 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙌 Special Thanks

- **ValuEnable** for organizing the hackathon  
- **Zerodha Rainmatter** for supporting InsureTech innovation  
- The open-source community for incredible libraries

---
