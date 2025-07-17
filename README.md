# YouTube-RAG-Chatbot (Notebook Version)

A proof-of-concept YouTube question-answering chatbot built using Retrieval-Augmented Generation (RAG), implemented in a Jupyter Notebook.

---
> ⚠️ Under maintenance / Development 
## 🧠 Overview

This project demonstrates how Retrieval-Augmented Generation (RAG) can be applied to video content — specifically YouTube videos — by allowing users to ask questions about a video's content and get accurate, context-aware answers.

Instead of generating answers solely based on model memory, the system retrieves relevant information from a processed video transcript and feeds it into a generative language model to ground the response.

---

## 📓 Current Status

This version is built entirely in a Jupyter Notebook as a working prototype. It’s intended for experimentation and educational purposes. A modular Python package and interactive frontend will be added in future iterations.

---
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=Jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Transformers-HuggingFace-yellow?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/FAISS-Indexing-9cf?style=for-the-badge&logo=facebook&logoColor=white" />
  <img src="https://img.shields.io/badge/Colab-Supported-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white" />
  <img src="https://img.shields.io/badge/Notebook-Based-Prototype-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Open%20Source-Yes-brightgreen?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/github/last-commit/shivamprasad1001/YouTube-RAG-Chatbot?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/github/stars/shivamprasad1001/YouTube-RAG-Chatbot?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/github/forks/shivamprasad1001/YouTube-RAG-Chatbot?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-blueviolet?style=for-the-badge&logo=github" />
</p>


## 🔧 Features

- Accepts YouTube video transcripts as input
- Embeds and indexes transcript data using vector similarity (e.g., FAISS or SentenceTransformers)
- Retrieves relevant chunks based on user queries
- Uses a RAG pipeline to generate grounded responses
- Works fully within a Jupyter Notebook

---

## 🧰 Tech Stack

- Python 3.x
- Hugging Face Transformers (`RAG`, `Bart`, or `T5`)
- SentenceTransformers / FAISS
- YouTube Transcript API (or manual transcript upload)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repo:

```bash
git clone https://github.com/yourusername/YouTube-RAG-Chatbot.git
cd YouTube-RAG-Chatbot
````

2. Open the notebook:

```bash
jupyter notebook rag_youtube_chatbot.ipynb
```

3. Follow the cells to:

   * Load transcript
   * Chunk and embed
   * Ask a question
   * Get RAG-generated answers

---

## 📈 Future Improvements

* Convert notebook to modular Python scripts
* Add UI for video upload and chatting
* Automatic transcript extraction via YouTube API
* Add support for multilingual videos
* Dockerize for easy deployment

---

## 📝 License

MIT License

---

## ✉️ Contact

Created by **Shivam Prasad**
📧 Email: [your.email@example.com](mailto:your.email@example.com)
🌐 Portfolio: [shivamprasad.netlify.app](https://shivamprasad.netlify.app)
🐙 GitHub: [shivamprasad1001](https://github.com/shivamprasad1001)


