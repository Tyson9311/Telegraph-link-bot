# Telegraph Bot 🤖

A simple Telegram bot that converts media sent in chats to [Telegra.ph](https://telegra.ph) links using Pyrogram.

---

## 🔧 Features

- Uploads photos, videos, and other media to Telegra.ph
- Returns the shareable Telegraph link instantly
- Easy to deploy via Docker or on StackHost

---

## 🛠 Requirements

- Python 3.10+
- Telegram Bot Token
- Telegram API ID & API Hash from [my.telegram.org](https://my.telegram.org)
- Docker (for containerized deployment)

---

## 🚀 Local Setup

1. Clone the repo and navigate to it:
   ```bash
   git clone https://github.com/your-username/telegraph-bot.git
   cd telegraph-bot
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt
3. Add your credentials in telegraph_bot.py or set them as environment variables:
   ```bash
   export API_ID=your_api_id
   export API_HASH=your_api_hash
   export BOT_TOKEN=your_bot_token
4. Run the Bot:
   ```bash
   python telegraph_bot.py
