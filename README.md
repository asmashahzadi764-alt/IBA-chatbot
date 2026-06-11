# 🤖 IBA Sukkur AI Chatbot

An AI-powered chatbot developed to assist students, applicants, and visitors with queries related to IBA Sukkur. The chatbot leverages a Retrieval-Augmented Generation (RAG) architecture to provide accurate, context-aware, and institution-specific responses.

This project was developed as a collaborative team project, combining a modern React frontend with an AI-powered backend powered by FastAPI, LangChain, FAISS, and Groq LLM.

---

## 🌐 Live Demo

[![Frontend](https://img.shields.io/badge/🌐%20Frontend-Live%20Demo-6C63FF?style=for-the-badge)](https://iba-chat.vercel.app/)
[![Backend](https://img.shields.io/badge/🚀%20Backend-Streamlit%20Demo-00C9FF?style=for-the-badge)](https://ibasukkurchatbot.streamlit.app/)

---

## 🚀 Project Highlights

✅ Context-aware AI responses using RAG

✅ FastAPI-powered backend API

✅ React-based chatbot interface

✅ FAISS vector search for efficient retrieval

✅ LangChain workflow integration

✅ Groq LLM for response generation

✅ Responsive and user-friendly design

✅ Scalable architecture for future enhancements

---

## 🧠 How It Works

The chatbot retrieves relevant information from a vector database and combines it with a Large Language Model (LLM) to generate grounded and accurate responses.

```text
User Query
     │
     ▼
HuggingFace Embeddings
     │
     ▼
FAISS Vector Search
     │
     ▼
Relevant Context Retrieved
     │
     ▼
LangChain + Groq LLM
     │
     ▼
AI Generated Response
```

---

## 🛠 Technology Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-FF6B6B?style=for-the-badge&logo=meta&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

| Category        | Technologies                                |
| --------------- | ------------------------------------------- |
| Frontend        | React, JavaScript, CSS, Vite                |
| Backend         | FastAPI, Python                             |
| AI / NLP        | LangChain, HuggingFace Embeddings, Groq LLM |
| Vector Database | FAISS                                       |
| Deployment      | Vercel, Streamlit                           |

---

## ✨ Features

### 🎨 Frontend Features

* Interactive chatbot interface
* Floating chat widget
* Quick reply buttons
* Typing indicator
* Responsive design
* Clean and modern UI
* API integration with backend services

### ⚙️ Backend Features

* FastAPI REST API
* Retrieval-Augmented Generation (RAG)
* FAISS-based semantic search
* HuggingFace Embeddings
* LangChain orchestration
* Groq LLM integration
* Swagger API documentation

---

## 📂 Project Structure

```bash
IBA-chatbot
│
├── chatbot-ui-frontend
│   ├── src
│   ├── public
│   ├── package.json
│   ├── vite.config.js
│   └── README.md
│
├── IBA_Sukkur_Chatbot_Backend-main
│   ├── api
│   ├── services
│   ├── vectorstore
│   ├── main.py
│   ├── requirements.txt
│   └── .env
│
└── README.md
```

---

## ⚙️ Local Installation

### Clone Repository

```bash
git clone https://github.com/asmashahzadi764-alt/IBA-chatbot.git
cd IBA-chatbot
```

### Frontend Setup

```bash
cd chatbot-ui-frontend
npm install
npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

### Backend Setup

```bash
cd IBA_Sukkur_Chatbot_Backend-main
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend will run on:

```bash
http://127.0.0.1:8000
```

---

## 📡 API Endpoint

### POST /api/chat

#### Request

```json
{
  "message": "Admissions"
}
```

#### Response

```json
{
  "response": "AI generated response"
}
```

---

## 📖 API Documentation

FastAPI automatically generates interactive API documentation.

```bash
http://127.0.0.1:8000/docs
```

---

## 👥 Team

### Frontend Development & UI Integration

**Asma Shahzadi**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/asma-shahzadi-313291376/)

* Developed the complete React frontend
* Designed and implemented chatbot UI
* Created responsive user interface
* Integrated frontend with backend APIs
* Improved chatbot interaction experience
* Deployed frontend using Vercel

---

### Backend Development & AI Pipeline

**Hasnain Yaqub**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasnainyaqoob)

* Developed FastAPI backend
* Implemented Retrieval-Augmented Generation (RAG)
* Configured FAISS vector database
* Integrated HuggingFace Embeddings
* Integrated LangChain workflow
* Connected Groq LLM for response generation
* Developed Streamlit deployment

---

## ⚠️ Backend Deployment Note

The backend works successfully in the local development environment.

A public deployment of the complete RAG backend was not possible on free-tier hosting platforms due to memory limitations required by:

* HuggingFace Embedding Models
* FAISS Vector Store
* LangChain Components

The complete backend source code is included in this repository and can be executed locally using the setup instructions provided above.

---

## 📌 Portfolio Note

This repository contains the complete project source code for educational, demonstration, and portfolio purposes.

This was a collaborative team project. Frontend and backend contributions have been clearly acknowledged and credited to their respective contributors.

---

## 🏷️ Tags

`#AIChatbot` `#RAG` `#React` `#FastAPI` `#LangChain` `#FAISS` `#Groq` `#HuggingFace` `#Python` `#IBASukkur` `#PortfolioProject` `#FrontendDevelopment` `#ArtificialIntelligence`
