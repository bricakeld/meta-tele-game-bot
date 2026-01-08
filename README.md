# Telegram Echo Bot

A simple Telegram bot that echoes back whatever message you send it.

## Setup

### 1. Create a Telegram Bot

1. Open Telegram and search for [@BotFather](https://t.me/botfather)
2. Send `/newbot` and follow the prompts to create your bot
3. Copy the API token that BotFather gives you

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Environment Variable

Set your bot token as an environment variable:

```bash
export TELEGRAM_BOT_TOKEN="your-bot-token-here"
```

### 4. Run the Bot

```bash
python bot.py
```

## Usage

- `/start` - Start the bot and see the welcome message
- `/help` - Get help information
- Send any text message and the bot will echo it back to you

## Features

- Echoes any text message sent by users
- Simple and lightweight
- Uses polling mode (no webhook setup required)

