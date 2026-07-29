# 💎 Dormon Pro - VIP iOS Glass AI Workspace

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?logo=tailwind-css)
![Groq](https://img.shields.io/badge/Powered_By-Groq_API-orange)
![Single File](https://img.shields.io/badge/Architecture-Single_File-success)

**Dormon Pro** is a sleek, ultra-modern, iOS-inspired AI Chat Workspace built with a **VIP Glassmorphism UI**, dynamic interactive mouse spotlight glow, and blazing-fast response speeds powered by the **Groq API**.

---

## 📸 Screenshots & Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/822db540-bfcb-4610-8dd2-f759e1ac30bd" alt="Dormon Pro Overview" width="100%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/030bc38e-6d08-4e9c-bdca-2dd079615507" alt="Chat Experience" width="49%" />
  <img src="https://github.com/user-attachments/assets/472f025c-bb19-460e-9e9d-bb01a6806b85" alt="Settings Panel" width="49%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7eb80ce2-71a1-45e2-b9a2-14e08767d2ec" alt="Full Interface Preview" width="100%" />
</p>

---

## ✨ Key Features

* **🪟 Interactive iOS Glassmorphism UI:** Premium frosted glass aesthetic with an interactive mouse spotlight effect (`--mouse-x`, `--mouse-y`) that dynamically reacts to cursor movement.
* **⚡ Powered by Groq API:** Ultra-fast responses with built-in support for models like:
  * `llama-3.3-70b-versatile`
  * `llama3-8b-8192`
  * `mixtral-8x7b-32768`
* **📝 Markdown & Code Highlighting:** Rich text rendering via `Marked.js` and syntax highlighting via `Highlight.js` (GitHub Dark Dimmed theme).
* **🎙️ Voice Interaction:**
  * **Speech-to-Text:** Direct Urdu/English voice input using Web Speech API.
  * **Text-to-Speech:** Read AI responses out loud with a single click.
* **🛠️ Utility Functions:**
  * **Clear Chat (🗑️):** Reset conversation history in one click.
  * **Export Chat (📄):** Save your entire conversation as a `.txt` file.
  * **Fullscreen Mode (🔲):** Distraction-free interface for coding and reading.
  * **Quick Prompts (✨):** Contextual suggestion chips for rapid prompting.
  * **Attachment Button (📎):** Modern UI placeholder for upcoming file attachments.
  * **Stop Generation (🛑) & Regenerate (🔄):** Complete control over AI output generation.
* **💾 Local Persistence:** Chat history, selected API models, and system prompts are automatically saved to your browser's `localStorage`.

---

## 🛠️ Tech Stack

* **Frontend Framework:** React 18 (via CDN) & Babel Compiler
* **Styling:** Tailwind CSS (via CDN) + Custom CSS Variables & Animations
* **AI Engine:** Groq API (OpenAI Compatible Endpoint)
* **Parsers:** Marked.js & Highlight.js

---

## 🚀 Quick Start

Since this project runs entirely in the browser using CDN references, no installation (`npm install`) is required!

### Option 1: Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/sherazi924/codealpha_tasks.git](https://github.com/sherazi924/codealpha_tasks.git)
