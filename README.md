# 📰 NewsNinja — Real-Time AI News Summarizer with Voice

**NewsNinja** is a modern AI-powered web app that scrapes live news using **BrightData**, summarizes it using **Claude (Anthropic API)**, and reads the summary aloud using **ElevenLabs TTS**. It features a modular architecture using **FastAPI** (via `backend.py`), a clean **Streamlit UI (`frontend.py`)**, and a custom **Multi-Component Pipeline (MCP)** system to manage scraping, LLMs, and audio.

---

## 🚀 Live Demo

🌍 [Deployed Version](https://your-live-deployment.com) *(Add your own deployment URL)*

---

## 📸 Preview
<img width="1916" height="935" alt="image" src="https://github.com/user-attachments/assets/6567eff8-c9be-4f41-aee3-09c9ea87799a" />
<img width="1919" height="771" alt="image" src="https://github.com/user-attachments/assets/527b518d-a1a8-41ec-8256-8894f9b9a80b" />




---

## ✨ Key Features

- 🌐 **Live News Fetching** via BrightData Proxy API
- 🧠 **Summarization** using Claude (Anthropic API)
- 🔊 **Natural Voice Playback** using ElevenLabs
- ⚡ **Modular Backend** with LangChain + MCP
- 🖥️ **Streamlit UI** for both frontend and backend
- 📜 **FastAPI Swagger Docs** available at `/docs`

---

## 🛠️ Tech Stack

| Layer           | Technology                         |
|------------------|-------------------------------------|
| 📡 Scraper        | BrightData Proxy + News Queries     |
| 🧠 LLM            | Claude (Anthropic API)              |
| 🔊 Text-to-Speech | ElevenLabs API                     |
| 🧩 Pipeline       | Custom MCP with LangChain           |
| ⚙️ Backend        | FastAPI (served via Streamlit)      |
| 💻 Frontend       | Streamlit UI (`frontend.py`)        |

---

## 📁 Project Structure
├── backend.py # FastAPI + MCP backend (run with Streamlit)
├── frontend.py # Streamlit UI (user interface)
├── components/ # Streamlit UI components
├── utils/ # Scraping, TTS, and summarization modules
├── .env # API keys and config (not committed)
├── requirements.txt # Python dependencies
└── README.md # Documentation


---

## 🔧 Installation & Setup
streamlit run backend.py
✅ The FastAPI backend will start. You can access interactive API docs at:

streamlit run frontend.py

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/newsninja.git
cd newsninja


🧪 Example Use Cases
🧠 Quickly summarize breaking news

🗣️ Convert articles to voice and listen while commuting

📰 Build custom RSS-style readers powered by LLMs

🔍 Personal AI News Assistant for daily briefings

