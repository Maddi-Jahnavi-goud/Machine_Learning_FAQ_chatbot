# 🧠 Machine Learning Chatbot (Lecture Notes R17A0534)

This project is a **Streamlit-based Machine Learning Chatbot** that allows users to ask questions directly from their **Machine Learning lecture notes (PDF)**.  
It automatically loads and processes the notes file (`MACHINE LEARNING (R17A0534).pdf`) using **LangChain**, **HuggingFace embeddings**, and **OpenAI GPT models**, providing intelligent answers about Machine Learning concepts and algorithms.

---

## 🚀 Features
- 📘 Automatically loads Machine Learning notes (no manual upload needed)
- 🧩 Uses **LangChain** for document retrieval and conversation memory
- 🧠 Powered by **GPT-3.5-turbo** (via OpenRouter)
- 🔤 Handles non-ASCII symbols with full **UTF-8 encoding**
- 🌐 Deployable publicly using **Ngrok**
- 💬 Interactive chat interface built with **Streamlit**

---

## 🏗️ Project Structure
├── app.py # Main Streamlit application
├── MACHINE LEARNING(R17A0534).pdf # Lecture notes (used for chatbot training)
├── README.md # Project documentation
├── requirements.txt # Dependencies list

└── Machine_Learning_Chatbot_Project_Report.docx # Project report document

## Streamlit app 
1️⃣ Streamlit + OpenRouter API: The app loads your Machine Learning PDF, converts it to embeddings, and uses OpenRouter’s GPT model (via your API key) to answer questions in a conversational chat interface.
2️⃣ Ngrok Tunnel: It starts the Streamlit app locally and exposes it to the web with Ngrok, giving a public URL to access your chatbot from anywhere.
