# ✈️ Local AI Travel Recommendation Platform

A lightweight, privacy-focused travel planning web application built using Python, Streamlit, and local open-source Large Language Models (LLMs) via Ollama. 

This platform acts as an intelligent assistant that captures user preferences, logs the data for a Lead Management System, and queries an offline neural network to generate structured vacation suggestions.

## 🚀 Features
- **Local AI Brain:** Uses `qwen2.5:1.5b` via Ollama to generate context-aware destination plans completely offline.
- **Structured Data Engine:** Forces the LLM to output valid JSON objects for seamless application parsing.
- **Lead Generation System:** Captures user contact info (Name, Email) alongside travel parameters for client tracking.
- **Interactive UI:** Built with Streamlit for slick sliders, drop-down menus, and dynamic status spinners.

## 🛠️ Tech Stack
- **Frontend/Backend:** Python 3.12, Streamlit
- **AI Inference Engine:** Ollama (Qwen2.5-1.5B)
- **Environment Management:** Python Virtual Environments (`venv`)

## 📦 Local Installation & Setup

1. **Clone the project & navigate into the folder:**
   ```cmd
   git clone <your-repository-link>
   cd travel-ai-planner
   ```

2. **Create and activate the isolated virtual environment:**
   ```cmd
   python -m venv oiueo
   oiueo\Scripts\activate
   ```

3. **Install the required package dependencies:**
   ```cmd
   pip install streamlit ollama watchdog
   ```

4. **Ensure Ollama is running your local model:**
   Make sure the Ollama desktop agent is running in your system tray, or start it via terminal:
   ```cmd
   ollama run qwen2.5:1.5b
   ```

5. **Launch the web application dashboard:**
   ```cmd
   streamlit run oiuio.py
   ```

---
*Created as a high-density, privacy-centric AI application prototype.*
