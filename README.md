# 🧠 Adaptive Text Summarizer

A FastAPI-based text summarization system built using HuggingFace Transformers (T5). This application generates concise summaries from input text with optimized inference and real-time API interaction.

---

## 🚀 Features

- Transformer-based summarization using T5
- FastAPI backend for efficient API handling
- Text preprocessing (cleaning & normalization)
- Device-aware inference (CPU/GPU support)
- Beam search–based optimized text generation
- Simple and interactive frontend interface

---

## 🛠️ Tech Stack

- Backend: FastAPI (Python)
- Model: HuggingFace Transformers (T5)
- Frontend: HTML, CSS, JavaScript
- ML Framework: PyTorch

---

## ⚙️ How It Works

1. User inputs text through the web interface  
2. Input text is cleaned and normalized  
3. Tokenization is performed using T5 tokenizer  
4. Model generates summary using beam search  
5. Output is returned via API and displayed on UI  

---

## 📂 Project Structure
adaptive-text-summarizer/
│── app.py
│── index.html
│── README.md

---

## 📦 Installation

```bash
git clone https://github.com/samriddha1bits-ship-it/adaptive-text-summarizer.git
cd adaptive-text-summarizer
pip install fastapi uvicorn transformers torch
