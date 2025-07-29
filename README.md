# Build Your First AI Agent — Step-by-Step Guide

### 1️⃣ Install Docker

First, download and install **Docker** on your machine.

---

### 2️⃣ Run n8n Using Docker

Open your terminal and run the following commands:

```bash

docker pull n8nio/n8n

```

```bash
docker run -it --rm \
-p 5678:5678 \
-v ~/.n8n:/home/node/.n8n \
n8nio/n8n

```

You can also manage n8n using:

```bash
docker start n8n
docker stop n8n

```

Once running, access n8n in your browser at:

👉 [http://localhost:5678](http://localhost:5678/)

---

### 3️⃣ Set Up Your n8n Account

Follow the on-screen instructions to set up your n8n account.

---

### 4️⃣ Install VS Code

Download and install **Visual Studio Code** for writing and editing your code.

---

### 5️⃣ Install Required Packages

1. Install **Node.js** — this will also install **npm**.
2. Open your terminal and install the necessary packages:

```bash
npm install express venom-bot axios

```

---

### 6️⃣ Import Your Code

Copy your bot code into your VS Code project.

---

### 7️⃣ Import Your Agent Workflow into n8n

Upload the provided `.json` file to n8n to load your AI agent workflow.

---

### 8️⃣ Create a Test Function

Set up a test function to simulate interactions with your agent.

---

---

### 9️⃣ Setup Openrouter account

Set up your api key. And add your api key into your n8n credentials.

---

### 🔟 Test Your Workflow

1. **Enable workflow testing** in n8n.
2. Run your bot with:

```bash
node bot.js

```

1. Trigger the test using `curl`:

```bash
curl -X POST http://localhost:3000/simulate-self \
-H "Content-Type: application/json" \
-d '{"body": "Hi", "from": "your-phone-number@c.us"}'

```

---

✅ Done! Your AI agent is now ready for action.
 
# 💬 WhatsApp Messenger Bot

A powerful Python-based WhatsApp automation bot that simulates human-like messaging behavior. Perfect for learning, experimenting with Twilio/WhatsApp APIs, or personal automation tasks.

---

## 🚀 Features

- ✅ Send & receive WhatsApp messages
- ✅ Automatic replies based on keywords
- ✅ Easy-to-configure message triggers
- ✅ Extendable with custom Python logic
- ✅ Clean & modular codebase

---

## 📁 Project Structure


