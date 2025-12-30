# Ventri | AI English Coach 🚀

**Ventri** is an AI-powered communication coach designed to bridge the gap between vernacular speech and global professional fluency. Unlike traditional grammar checkers, Ventri understands cultural context, detects code-switching (like Hinglish or Tanglish), and helps users master IELTS speaking, writing, and job interviews.

## 📄 The Problem
India is a nation of 1.4 billion dreamers. Yet, for many, the transition from local dialects to global professional English is a massive barrier. "Hinglish" habits and a lack of confidence often prevent brilliant graduates from securing the global opportunities they deserve.

## 💡 The Solution
Ventri isn't just a spellchecker. It is a **cultural translator**.  
Powered by **Google Gemini 2.5 Flash**, it listens to your speech, detects specific Indian dialect patterns (e.g., "I am feeling tired-aa"), and gently guides you toward professional fluency without losing your unique voice.

## ✨ Key Features

### 🎙️ Speaking Practice
* **IELTS Speaking Task 2:** Simulates the "long turn" with generated cue cards.
* **Job Interview Mode:** Acts as an HR Manager, asking behavioral questions and evaluating answers using the **STAR method** (Situation, Task, Action, Result).
* **Real-time Dialect Detection:** Identifies code-switching (Tanglish, Hinglish, Singlish) and suggests formal alternatives.
* **Fillers & Fluency Analysis:** Detects hesitation markers ("uhh", "like") to improve speech flow.

### 📝 Writing Practice
* **IELTS Writing Task 2:** Generates academic essay prompts (Opinion, Problem/Solution, etc.) and scores based on official band descriptors (TR, CC, LR, GRA).
* **Business Communication:** Evaluates emails and reports for professional tone, conciseness (BLUF), and etiquette.

### 🧠 Smart Feedback Engine
* **Instant Scoring:** Provides Band Scores (5.0–9.0) or Hireability Scores (0–10).
* **Detailed Metrics:** Breakdown of Grammar, Vocabulary, and Coherence.
* **Native Bridge:** Translates complex vocabulary into native languages (Hindi, Tamil, Telugu, Malay, Mandarin, etc.) for deeper understanding.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Glassmorphism UI), Vanilla JavaScript.
* **AI Model:** Google Gemini 2.5 Flash (via Google AI Studio).
* **Audio Processing:** Web Speech API (Client-side Speech-to-Text) for privacy-focused, latency-free recording.
* **Architecture:** Serverless / Client-side only.

## 🚀 Getting Started

### Prerequisites
You need a [Google Gemini API Key](https://aistudio.google.com/app/apikey).

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/ventri.git](https://github.com/yourusername/ventri.git)
    cd ventri
    ```

2.  **Configure API Key**
    Open `index.html` in your code editor. Look for the configuration script block near the top:
    ```javascript
    const CONFIG = {
        // ========================================
        // INSERT YOUR GEMINI API KEY HERE:
        // ========================================
        GEMINI_API_KEY: 'YOUR_GEMINI_API_KEY' // <--- Paste your key here
    };
    ```

3.  **Run the App**
    Simply open `index.html` in any modern web browser (Chrome or Edge recommended for best Web Speech API support). No backend server is required!

## 🔮 Roadmap
* **Q3 2025:** Native Mobile App (iOS/Android) for offline practice.
* **Q4 2025:** Real-time Call Coaching (Zoom/Teams integration).
* **Q1 2026:** VR Public Speaking scenarios.

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---
*Built with ❤️ by Team Ventri for InnovHack.*
