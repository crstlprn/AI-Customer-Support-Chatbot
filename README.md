# AI-Customer-Support-Chatbot

An AI-powered customer support chatbot built in **Java** that connects to the OpenAI API to answer customer queries.  
This project demonstrates how to integrate GPT models into a simple Java command-line application.

---

## 📌 Features
- Connects to **OpenAI GPT-3.5 Turbo** for AI responses
- Command-line interface for easy interaction
- Reads API key from environment variable (no hardcoding)
- Error handling for missing or invalid keys

---

## 🛠️ Technologies Used
- **Java JDK 8+** (tested with OpenJDK 24)
- **OpenAI API**
- **HTTPURLConnection** for making API requests

---

## 📂 Project Structure
AI-Customer-Support-Chatbot/
├── ChatbotApplication.java # Main chatbot Java source code
├── .gitignore # Git ignore file
└── README.md # Project documentation (this file)


---

## 🚀 Getting Started

### 1️⃣ Prerequisites
- Install **Java JDK 8 or higher** ([Download Java](https://jdk.java.net/))
- An **OpenAI account** and API key ([Get your key here](https://platform.openai.com/account/api-keys))

---

### 2️⃣ Get an OpenAI API Key
1. Sign in to [OpenAI](https://platform.openai.com/)
2. Go to [API Keys](https://platform.openai.com/account/api-keys)
3. Click **Create new secret key**
4. Copy your API key (looks like `sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`)

---

### 3️⃣ Set the API Key as an Environment Variable

**Windows (CMD)**:
```cmd
setx OPENAI_API_KEY "sk-your-api-key"
