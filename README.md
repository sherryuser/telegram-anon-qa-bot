# 🤖 Telegram Anonymous Q&A Bot

This project houses a Telegram bot that allows users to engage in anonymous Q&A sessions. Users can send and receive questions without revealing their identities, fostering an environment where they can freely express themselves.

## Features 🌟

- **Anonymity** 🔒: Users can interact without disclosing their identity.
- **SQLite Database** 💾: Persistent storage of users and messages.
- **Interactive Replies** 💬: Recipients can reply directly to anonymous messages through a simple interface.

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites 📋

- Python 3.6 or higher
- `pip` for installing dependencies
- A Telegram bot token (obtainable through [BotFather](https://t.me/botfather))

### Installation 🔧

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/sherryuser/telegram-anon-qa-bot.git
   ```
2. Navigate to the cloned repository:
   ```
   cd telegram-anon-qa-bot
   ```
3. Install the required Python packages:
   ```
   pip3 install telebot
   ```
4. Update the `YOUR_TELEGRAM_BOT_API_KEY` placeholder in the bot script with your actual Telegram Bot API key.

### Running the Bot 🤖

To start the bot, run the following command in your terminal:

```
python main.py
```

The bot should now be running and listening for incoming messages.

## Usage 📝

- **/start** - Initiates the bot and provides users with their unique anonymous Q&A link.
- Users can click on the link to start sending anonymous questions.
- The bot handles anonymous message delivery and provides a reply interface.

## Contributing 🤝

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

Distributed under the MIT License. See `LICENSE` for more information.
