# 📰 News Companion

A conversational news chatbot built with **LangChain**, **NewsAPI**,**Node.js** and **Express.js**, .  
The bot summarizes articles and answers user queries using **Google Gemini API** and **HuggingFace models**, with session-based history tracking for follow-up questions.

---

##  Features
-  **News Search**: Fetches the latest articles using [NewsAPI](https://newsapi.org/).  
-  **Smart Summarization**: Summarizes articles with **Google Gemini API** + **HuggingFace models** via LangChain.  
-  **Conversational Memory**: Tracks session history to support follow-up questions.  
-  **Express.js Backend**: Lightweight and fast API server.  

---

## Tech Stack
- **Backend**: Node.js, Express.js  
- **AI/LLM**: LangChain, Google Gemini API, HuggingFace Transformers  
- **News Source**: NewsAPI  
- **Environment**: dotenv for config, npm for package management  

---

## ⚙️ Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Vyshhh/news_bot_ai.git
   cd news-companion
   ```
2.Install dependencies
```bash
npm install
```
3.Add environment variables
-Create a .env file in the project root.
```env
NEWSAPI_KEY=your_newsapi_key
GEMINI_API_KEY=your_gemini_key
HUGGINGFACE_API_KEY=your_hf_token
```
4.Run the server
```bash
npm start

