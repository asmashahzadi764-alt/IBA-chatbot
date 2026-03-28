# 🤖 IBA Sukkur AI Chatbot

An **AI-powered chatbot** designed to assist users with queries related to **IBA Sukkur**.
This project includes a **React frontend chatbot interface** and a **FastAPI backend API** that processes user queries and returns AI-generated responses.

---

## 📌 Project Overview

The system consists of **two main components**:

### 💻 Frontend (React)

A **floating chatbot interface** integrated into a React application that allows users to interact with the AI assistant.

### ⚡ Backend (FastAPI)

A **Python-based API** that processes user messages and returns AI-generated responses using a **Retrieval-Augmented Generation (RAG)** architecture.

---

## 🚀 Features

### 🎨 Frontend Features

* **Floating chatbot widget**
* **Quick reply buttons**
* **Typing indicator**
* **Responsive user interface**
* **Clean and modern design**
* **Formatted chatbot responses**

### 🔧 Backend Features

* **FastAPI REST API**
* **Retrieval-Augmented Generation (RAG)**
* **FAISS vector database for document retrieval**
* **Structured API endpoints**
* **Automatic API documentation with Swagger UI**

---

## 📂 Project Structure

### 📁 Frontend

```
react-chatbot-frontend
│
├── public
│   └── index.html
├── src
│   ├── Chatbot.jsx        # Main chatbot component
│   ├── Chatbot.css        # Styling for chatbot
│   └── App.jsx            # Main React application
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

---

### 📁 Backend

```
IBA_Sukkur_Chatbot_Backend
│
├── api
├── services
├── vectorstore
│
├── main.py
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/react-chatbot-frontend.git
cd react-chatbot-frontend
```

---

## 💻 Frontend Setup

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

### Open in browser

```
http://localhost:5173
```

---

## ⚡ Backend Setup

### Install Python dependencies

```bash
pip install -r requirements.txt
```

### Run the FastAPI server

```bash
uvicorn main:app --reload
```

### Server runs at

```
http://127.0.0.1:8000
```

---

## 🔗 API Endpoint

### `POST /api/chat`

#### Request Example

```json
{
  "message": "Your question here"
}
```

#### Response Example

```json
{
  "response": "AI answer"
}
```

---

## 📖 API Documentation

FastAPI automatically generates **interactive API documentation**.

Open in browser:

```
http://127.0.0.1:8000/docs
```

---

## 🛠 Technologies Used

### 🎨 Frontend

* **React**
* **CSS**
* **Vite**

### ⚙️ Backend

* **Python**
* **FastAPI**
* **FAISS Vector Database**
* **Retrieval-Augmented Generation (RAG)**

---



