# 🎙️ DrX Voice Typing

**DrX Voice Typing** is a modern, real-time speech-to-text web application that converts your spoken words into written text with high accuracy. Built with a sleek glass-morphism UI, it offers multilingual speech recognition, AI-powered text processing, and a range of utility tools to enhance your productivity.

**Live Demos:** [Netlify](https://drxvoice.netlify.app/) | [GitHub Pages](https://seadib.github.io/voice/)

---

## ✨ Key Features

- **Real-time Voice Typing** – Instantly transcribes speech to text using the Web Speech API. Supports **Bengali (বাংলা)** and **English**.
- **AI-Powered Tools** – Leverage advanced language models to:
  - **Translate** text between Bengali and English.
  - **Rewrite & Refine** text for clarity and natural flow.
  - **Generate Intelligent Answers** to your queries.
- **Multi-Model AI Selection** – Choose from multiple backend AI models (Base, Pro 1.0, Pro 2.0, Plus) for different performance and capability levels.
- **Smart Text Management** – Copy, save as `.txt`, or clear the main text area with one click.
- **History Panel** – Automatically logs all original and AI-generated texts for easy reference and copying.
- **Theme Toggle** – Switch seamlessly between Dark and Light modes with persistent preference storage.
- **Responsive UI** – Clean, glass-morphism design with smooth animations and a developer-friendly layout.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Custom), JavaScript (ES6+)
- **Speech Recognition**: Web Speech API
- **AI Backend**: Groq API (`llama-3.3-70b-versatile`) & Google Gemini API (`gemini-2.5-flash-lite` & `gemini-flash-latest`)
- **Libraries**: FontAwesome Icons, Google Fonts (Outfit)
- **Deployment**: Netlify & GitHub Pages
- **Version Control**: Git & GitHub

---

## 🚀 Getting Started

### Prerequisites
- A modern browser (Chrome recommended for best speech recognition support).
- Internet connection for AI features.

### Running Locally
1.  Clone the repository:
    ```bash
    git clone https://github.com/yourusername/drx-voice-typing.git
    cd drx-voice-typing
