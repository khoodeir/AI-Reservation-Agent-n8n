# 🤖 AI Reservation Agent

An AI-powered reservation assistant built with **n8n**, **Google Gemini**, **Telegram**, **Google Calendar**, and **Google Sheets**.

The assistant can communicate with users through Telegram, understand both text and voice messages, answer questions, check reservations, and create new appointments automatically.

---

# 🚀 Features

- 💬 Chat with users through Telegram
- 🎤 Voice message support (Speech-to-Text)
- 🧠 AI-powered conversations using Google Gemini
- 📅 Automatically create reservations in Google Calendar
- 📊 Read reservation data from Google Sheets
- 🧾 Conversation memory
- ⚡ Fully automated n8n workflow

---

# 🏗️ Workflow

1. User sends a message on Telegram
2. The workflow detects whether the message is text or voice
3. Voice messages are converted to text
4. Google Gemini processes the request
5. The AI Agent decides which tool to use
6. Reservation data is retrieved from Google Sheets
7. New appointments are created in Google Calendar
8. The response is sent back to Telegram

---

# 🛠️ Tech Stack

- n8n
- Google Gemini
- Telegram Bot API
- Google Calendar API
- Google Sheets API

---

# 📂 Project Structure

```
workflow/
│
├── reservation-agent.json
│
README.md
```


---

# Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Reservation-Agent-n8n.git
```

2. Import the workflow into n8n

3. Configure your credentials:

- Telegram Bot
- Google Gemini API
- Google Calendar
- Google Sheets

4. Activate the workflow

---

# Example Conversation

User

> I want to reserve tomorrow at 4 PM.

Assistant

> Your reservation has been created successfully.

---

# Future Improvements

- WhatsApp integration
- Voice response (Text-to-Speech)
- Email confirmation
- Multi-language support
- Database integration
- Admin dashboard

---

# Author

Ahmed Khodeir

AI & Data Analysis Engineer
