# 🧠 AI Virtual Assistant (FastAPI + LLaMA 2 + HTML Frontend)

This is a lightweight AI-powered virtual assistant web app built with **FastAPI** and **LLaMA 2 (via Ollama)**. The assistant can:
- Chat and answer general queries.
- Schedule tasks based on natural language instructions (e.g., “Remind me to call mom tomorrow”).

## ⚙️ Features

- 🔌 FastAPI backend
- 💬 Natural language interaction with LLaMA 2 model via Ollama
- 📅 In-memory task scheduling from user input
- 🌐 Simple HTML/CSS/JS frontend
- 📦 Easy to run locally (no database or frontend frameworks required)

---

## 🖥️ Interface

| Function         | Description                                               |
|------------------|-----------------------------------------------------------|
| `/`              | Serves the frontend (`index.html`)                        |
| `/chat`          | Handles POST requests, sends prompts to LLaMA 2, returns response and task list |

---


---

## 🚀 Quick Start

### 1. 🧠 Prerequisites

- Python 3.8+
- [Ollama](https://ollama.com/) installed and running locally
- A local model like `llama2` pulled via:

```bash
ollama pull llama2


