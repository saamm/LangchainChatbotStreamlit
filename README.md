# 💬 Generative AI Chatbot (Streamlit + LangChain + Groq)

A simple conversational AI chatbot built using **Streamlit** and **LangChain**, powered by **Groq LLMs**.
This app maintains chat history and provides a ChatGPT-like interface.

---

## 🚀 Features

* 🧠 LLM-powered responses (Groq - LLaMA 3)
* 💬 Chat-style UI using Streamlit
* 📝 Persistent chat history (session-based)
* 🔐 Secure API key management with `.env`
* ⚡ Fast inference with Groq

---

## 🛠️ Tech Stack

* `streamlit` → UI
* `python-dotenv` → environment variables
* `langchain-community` → LLM integration
* `langchain-groq` → Groq model access

---

## 📂 Project Structure

```
ChatbotWithLangchain/
│
├── chatbot.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/saamm/LangchainChatbotStreamlit.git
cd LangchainChatbotStreamlit
```

---

### 2. Create virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate   # Windows
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Add API Key

Create a `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

### 5. Run the app

```bash
streamlit run chatbot.py
```

---

## 🧠 How It Works

1. User enters a query via Streamlit chat input
2. Query is saved to `chat_history`
3. Full chat history is sent to the LLM
4. LLM generates a response
5. Response is saved back to `chat_history`
6. Response is displayed in UI

---


---

## 📌 Requirements

```
streamlit
python-dotenv
langchain-community
langchain-groq
```

---

## ⚡ Future Improvements

* Streaming responses (typing effect)
* Memory optimization (long conversations)
* UI enhancements (avatars, themes)
* Multi-model support
* Deployment (Streamlit Cloud / Docker)

---

## 🧠 Key Learning

* Managing conversational state in Streamlit
* Passing structured chat history to LLMs
* Integrating Groq with LangChain
* Building real-time AI applications

---

## 📄 License

MIT License
