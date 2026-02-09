<div align="center">

# 🎓 RAG-Based College FAQ Chatbot with LLMs

### Retrieval-Augmented Generation chatbot for accurate college information

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-⚡-green)
![LLM](https://img.shields.io/badge/LLM-Groq-purple)
![License](https://img.shields.io/github/license/0xYuvi21/FAQ-chatbot)
![Stars](https://img.shields.io/github/stars/0xYuvi21/FAQ-chatbot?style=social)

A simple yet powerful **RAG-based chatbot** built with **FastAPI** and **Python**, designed to provide accurate and grounded answers about  
**SRM Madurai College of Engineering and Technology** using a local knowledge base and **Groq LLMs**.

</div>

---

##  Features

- 🏫 **College Information Retrieval**  
  Answers questions using structured data loaded from `college_info.json`.

- 🧠 **Retrieval-Augmented Generation (RAG)**  
  Grounds LLM responses in verified college data to reduce hallucinations.

- ⚡ **Groq API Integration**  
  Uses Groq’s high-speed inference engine for fast and efficient LLM responses.

- 🧩 **FastAPI Backend**
  - Automatic request validation with **Pydantic**
  - Asynchronous request handling
  - CORS middleware for frontend integration

- 🌐 **Simple Frontend**  
  Lightweight **HTML + CSS + JavaScript** interface for user interaction.

---

## 🛠️ Tech Stack

### Backend
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-green)
![Pydantic](https://img.shields.io/badge/Pydantic-data_validation-orange)
![Uvicorn](https://img.shields.io/badge/Uvicorn-ASGI_server-lightgrey)
![Groq](https://img.shields.io/badge/Groq-LLM-purple)

### Frontend
![HTML](https://img.shields.io/badge/HTML5-orange)
![CSS](https://img.shields.io/badge/CSS3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

---

## 📦 Prerequisites

- Python 3.9+
- pip (Python package installer)
- A **Groq API Key**  
  👉 Get one from the Groq Console

---

## 📥 Installation

```bash
git clone https://github.com/0xYuvi21/FAQ-chatbot.git
cd FAQ-chatbot
pip install -r requirements.txt
