# 🤖 File to Link Generator Bot

Hi there! I'm **Zara**, a powerful Telegram bot  helps users convert any file into a **direct download link**, **stream link**, and a **Telegram shareable link**. ✨

---

## 🚀 Features

- 📤 Upload any **video**, **photo**, **audio**, or **document** (up to 4GB)
- 🔗 Get a **direct download link**
- 📺 Get a **stream link** for files under 20MB
- 📬 Get a **Telegram shareable link**
- 💡 No need for your friends to have Telegram to access files!

---

## 🛠 Setup Instructions

Follow these steps to deploy the bot using **Cloudflare Workers**:

### 1️⃣ Clone this repo
```bash
git clone https://github.com/your-username/zara-link-bot.git
```

### 2️⃣ Replace the following values in `workers.js`:

```javascript
const BOT_TOKEN = "";        // 👉 Your Telegram Bot Token
const BOT_SECRET = "secret"; // 👉 A secure random string
const BOT_CHANNEL = ;        // 👉 Your Telegram Channel ID (as an integer)
const SIA_NUMBER = 1234;     // 👉 A random secret integer (same across bot & backend)
const BOT_OWNER = "YourUserName"; // 👉 Your Telegram username (for /start button)
```

> 📝 Make sure your bot is added as an admin in your channel.

---

### 3️⃣ Deploy on Cloudflare Workers

1. Copy-paste the `workers.js` file into the [Cloudflare Workers editor](https://dash.cloudflare.com/)
2. Save and deploy the worker.

---

### 4️⃣ Register Webhook

Go to:
```
https://your-domain.com/registerWebhook
```

✅ If everything is okay, it will return:
```json
{"ok":true,"result":true,"description":"Webhook was set"}
```

Your bot is now live and ready to use!

---

## 📸 Demo Screenshots
<img src="https://github.com/user-attachments/assets/dd705453-2f01-46a6-b2b5-e9357e997891" width="200" />
<img src="https://github.com/user-attachments/assets/e3c13eee-e49e-43a9-857d-1b4ad00f79cb" width="200" />
<img src="https://github.com/user-attachments/assets/757d987d-38d6-48fe-94a4-f8a9f24eafff" width="200" />
<img src="https://github.com/user-attachments/assets/567a4ce3-9881-48de-beac-ee0893064ac3" width="200" />
<img src="https://github.com/user-attachments/assets/6078b191-d684-409b-a385-8096490bfb72" width="200" />


---

## 🤖 Try the Bot

👉 [Click here to test the demo bot](https://t.me/Zara_TBot)

---

## 🧑‍💼 Contact

For help or inquiries, feel free to [contact the bot owner](https://t.me/NipunSGeeTH).

---

## 📜 License

This project is open-source under the MIT License. You’re free to use, modify, and share it!

---

## ❤️ Thanks for using Zara!


