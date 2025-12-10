

# 🔎 LangChain Search Engine LLM (Streamlit + Groq)

A smart search-based AI chatbot built using Streamlit, LangChain, and Groq’s LLaMA models. This application can search the web, Wikipedia, and arXiv to provide accurate answers in real time.

---

## 🚀 Features

• Interactive chat interface
• Web search using DuckDuckGo
• Wikipedia knowledge search
• arXiv research paper search
• Live agent reasoning visibility
• Streaming AI responses

---

## 🛠️ Tech Stack

Python
Streamlit
LangChain
Groq API
DuckDuckGo Search
Wikipedia API
arXiv API
dotenv

---

## 📁 Project Structure

langchain-search-engine-llm/
├── app.py
├── requirements.txt
├── .env.example
├── README.md
└── LICENSE

---

## ⚙️ Installation

Clone the repository and navigate into it.

Create and activate a virtual environment.

Install required dependencies using requirements.txt.

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

Add your Groq API key:

GROQ_API_KEY=your_api_key_here

Do not upload this file to GitHub.

---

## ▶️ Running the Application

Run the Streamlit app using:

streamlit run app.py

Open your browser and go to:

[http://localhost:8501](http://localhost:8501)

---

## ⚡ How It Works

• User enters a query
• LangChain agent decides which tool to use
• Fetches data from search engines
• Groq LLM processes the result
• Final response is shown to the user

---

## 🧑‍💻 Author

Sarthak Kelkar
GitHub: [https://github.com/EasySarthak1440](https://github.com/EasySarthak1440)

---



