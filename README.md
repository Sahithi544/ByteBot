# ByteBot
Multilingual voice-based AI insurance chatbot for InsureBot Quest 2025.
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
