# 🤖 AI Chatbot using ChatGPT API (HTML, CSS, JS Only)

A lightweight and smart AI chatbot built using **pure HTML, CSS, and JavaScript**, powered by **OpenAI's ChatGPT API**. No backend needed — just plug in your API key and start chatting!

## 🧠 Features

- ⚡ Simple, fast, and frontend-only setup
- 💬 Smart conversation using OpenAI ChatGPT API
- 🧱 Built using HTML, CSS, JavaScript (No frameworks)
- 🎨 Clean and responsive UI
- 🔐 Easy to integrate with your own OpenAI API key

## 📸 Demo

> Add a live demo link or screenshot here (optional)


## 📂 Folder Structure

📁 your-chatbot-folder/
├── index.html
├── style.css
├── script.js
└── README.md



## 🚀 Getting Started

1. **Clone this repository**

```bash
git clone https://github.com/yourusername/ai-chatbot-html-js.git
cd ai-chatbot-html-js


const API_KEY = "YOUR_OPENAI_API_KEY";



Open index.html in your browser

That’s it! Your chatbot is ready to use.

🔐 Get OpenAI API Key
Go to OpenAI API Keys

Log in or sign up

Create a new secret key

Paste it into your JavaScript file

💡 How It Works
The user types a message

JavaScript sends a fetch request to OpenAI's https://api.openai.com/v1/chat/completions endpoint

OpenAI sends back the response from ChatGPT

The bot reply is displayed in the chat window

📃 Sample API Request (used in script.js)




fetch("https://api.openai.com/v1/chat/completions", {
  method: "POST",
  headers: {
    "Content-Type": "application/json",
    "Authorization": `Bearer ${API_KEY}`
  },
  body: JSON.stringify({
    model: "gpt-3.5-turbo",
    messages: [{ role: "user", content: userInput }],
  })
});
📄 License
This project is open-source and free to use under the MIT License.
