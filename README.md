NestJS Telegram Bot 🤖

This is a simple Telegram bot built using NestJS and node-telegram-bot-api. The bot listens for incoming messages and can send messages to specific users.


Features ✨
📩 Listens for incoming messages from Telegram users.
📜 Logs received messages to the console.
📤 Sends messages to specific users.
 
Prerequisites 📌
🟢 Node.js (>= 16.x recommended)
📦 npm or yarn
🔑 A valid Telegram bot token from BotFather

Installation 🛠️
Clone the repository and install dependencies:
git clone <repository_url>
cd <project_directory>
npm install

Configuration ⚙️
Replace the TELEGRAM_TOKEN in telegram.service.ts with your actual Telegram bot token:
const TELEGRAM_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN";
WEATHER_API_KEY= "YOUR_WEATHER_API_KEY";

Running the Bot 🚀
To start the bot in development mode:
npm run start:dev

Usage 📖
Sending and Receiving Messages 💬
First : user needs to enter /start which will show "🌍 Welcome! Use /subscribe to receive daily weather updates."
Second : "📍 Please enter your city name:"
Third : "✅ You have subscribed to daily weather updates for ${city name}.Please enter /weather to get the current weather."
Fourth : Use /unsubscribe if user want to unsubscribe and it will show "❌ You have unsubscribed from daily weather updates."