# 🚀 JS Daily Byte

Daily JavaScript concepts. Automated.

JS Daily Byte is a zero-server Telegram bot powered by GitHub Actions that posts one JavaScript quote every day to the **JS Daily Byte** group.

## 🔗 DEV Article

https://dev.to/sushantrahate/js-daily-byte-a-daily-javascript-quote-bot-built-with-github-actions-pol

## 💬 Live

Telegram Group: https://t.me/jsdailybyte

## 🧠 Example Message

```
🟡 JS Daily Byte

“Every JavaScript program runs inside an execution context with two
phases: memory creation and code execution.”
```

## ⚙️ How It Works

1. Reads `quotes.json` (array of JavaScript concepts)
2. Generates a deterministic index using the current UTC date
3. Selects the corresponding quote
4. Escapes HTML for Telegram-safe formatting
5. Sends the message using the Telegram Bot API via `curl`

## 🏗 Tech Stack

- GitHub Actions (daily scheduler)
- Node.js (inline workflow script)
- Telegram Bot API
- JSON-based quote storage

## ⏱ Under 30 Minutes to Build

No database.  
No server.  
No maintenance.

A Telegram bot.  
A JSON file.  
A GitHub Action.

If you liked it then please show your love by ⭐ the repo
