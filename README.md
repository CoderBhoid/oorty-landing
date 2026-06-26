# Sednium Oorty — Landing Page

> Multi-Model AI Chat & Coding Orchestration Platform. Connect to 8+ AI providers, run local models, and orchestrate workflows through a single, elegant interface.

[![Website](https://img.shields.io/badge/website-oorty.sednium.com-brightgreen)](https://oorty.sednium.com)
[![Publisher](https://img.shields.io/badge/publisher-sednium.com-orange)](https://sednium.com)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🌟 Overview

**Sednium Oorty** is a powerful, elegant, and warm editorial-styled AI chat and coding orchestration platform built to harness multiple large language models seamlessly. This repository contains the source code for the public-facing landing page hosted at [oorty.sednium.com](https://oorty.sednium.com).

The application features a distinctive visual identity utilizing a rich Milk White (`#FDFBF7`) background, warm editorial typography (`Source Serif 4` and `Crimson Pro`), and vibrant Orange (`#EC5E27`) accents.

---

## 🚀 Key Features of Oorty

1. **Multi-Model Orchestration**
   * Powered by the proprietary **Sednium Rosette API** for intelligent routing, chaining, and combining multiple AI models.
2. **Multi-Provider & Model Support**
   * Connect to **Google Gemini**, **OpenAI**, **Anthropic**, **xAI**, **Groq**, **OpenRouter**, **NVIDIA NIM**, **Ollama** (local), and browser-native models.
3. **Specialized Chat Modes**
   * **Quick Mode:** Maximal speed, precision, and brevity.
   * **Thinking Mode:** Deep, rigorous chain-of-thought analytical reasoning.
   * **Coding Mode:** Elite software architect mode for clean, robust, and highly optimized code.
4. **Custom System Instructions**
   * Fine-tune the AI's behavior by appending custom system instructions on top of the selected Chat Mode.
5. **Configuration Presets**
   * Save favorite configurations (Model Provider + Model + Chat Mode + System Instructions) for rapid switching.
6. **Local AI & Hugging Face Integration**
   * Run open-source models locally via Ollama and LM Studio. Download, cache, and run models directly from the Hugging Face Hub.
7. **Privacy-First**
   * All API keys and conversation history are stored locally in your browser. No data is sent to Sednium servers.

---

## 📂 Repository Structure

```text
├── assets/            # Brand assets, logos, and custom fonts
├── css/               # Styling sheets (Vanilla CSS design system)
├── js/                # Interactive landing page logic
├── public/            # Publicly served assets & SEO files
│   ├── robots.txt     # Crawler instructions
│   ├── sitemap.xml    # Search engine sitemap
│   ├── ai.txt         # Machine-readable AI crawler info
│   └── llm.txt        # LLM-readable description of the platform
├── index.html         # Main landing page entrypoint
└── README.md          # This documentation
```

---

## 🛠️ Getting Started

### Run Locally

Since the landing page is built using vanilla HTML, CSS, and JavaScript, you can run it locally without any build step or package installations:

1. Clone this repository:
   ```bash
   git clone https://github.com/CoderBhoid/oorty-landing.git
   cd oorty-landing
   ```
2. Open `index.html` in your browser, or run a simple local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (npx)
   npx serve .
   ```
3. Access the page at `http://localhost:8000` (or the port specified by your server).

### Deploying

You can deploy this static landing page to any hosting provider (GitHub Pages, Vercel, Netlify, Cloudflare Pages, etc.) by linking your GitHub repository. The SEO files in the `public/` directory should be mapped to the root directory during deployment configs if your host requires it.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🤝 Contact

* **Publisher:** [Sednium](https://sednium.com)
* **Support:** [support@sednium.com](mailto:support@sednium.com)
* **GitHub Organization:** [CoderBhoid](https://github.com/CoderBhoid)
