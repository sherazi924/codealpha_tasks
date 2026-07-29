# 💎 Dormon Pro - VIP iOS Glass AI Workspace (Task 2)

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?logo=tailwind-css)
![Groq](https://img.shields.io/badge/Powered_By-Groq_API-orange)
![Single File](https://img.shields.io/badge/Architecture-Single_File-success)

**Dormon Pro** is an advanced, ultra-modern, iOS-inspired AI Chat Workspace built with a **VIP Glassmorphism UI**, dynamic interactive elements, and lightning-fast response speeds powered by the **Groq API**. Developed as part of Task 2.

---

## ✨ Key Features

* **🪟 Interactive iOS Glassmorphism UI:** Premium frosted glass aesthetic with fluid animations.
* **⚡ Powered by Groq API:** Ultra-fast inference with support for models like `llama-3.3-70b-versatile`, `llama3-8b-8192`, and `mixtral-8x7b-32768`.
* **📝 Markdown & Code Highlighting:** Rich text rendering via `Marked.js` and syntax highlighting via `Highlight.js` (Tokyo Night theme).
* **🎙️ Voice Interaction:** 
  * **Speech-to-Text:** Urdu/English voice input using the Web Speech API.
  * **Text-to-Speech:** Listen to AI responses read aloud instantly.
* **🛠️ Advanced Utilities:**
  * **Stop Generation (🛑) & Regenerate (🔄):** Full control over AI stream generation.
  * **Export Chat (📄):** Save your conversation history as a `.txt` file.
  * **Smart Word & Character Counter:** Real-time stats for input messages.
  * **Local Persistence:** Chat history, API keys, and preferences saved securely via `localStorage`.

---

## 🛠️ Tech Stack

* **Frontend Framework:** React 18 (via CDN) & Babel Compiler
* **Styling:** Tailwind CSS (via CDN) + Custom Animations
* **AI Engine:** Groq Cloud API
* **Parsers:** Marked.js & Highlight.js

---

## 🚀 Quick Start

1. Open the `Task 2` folder and ensure `index.html` is properly placed.
2. Open `index.html` directly in any modern web browser.
3. Click the **Settings (⚙️)** icon in the top header, paste your **Groq API Key (`gsk_...`)**, and start chatting with Dormon Pro!
