# Documentation

[![Open In Collab](https://raw.githubusercontent.com/Damarcreative/TeleBot-GPT/674fe7fea86dd29e8b66b3d9069d2ff4f501cac0/badge/colab-badge.svg)](https://colab.research.google.com/drive/1p-6whVjMSoBcN9Rv0JbQDZiKDvAUNP0x)  [![Open In Collab](https://raw.githubusercontent.com/Damarcreative/TeleBot-GPT/674fe7fea86dd29e8b66b3d9069d2ff4f501cac0/badge/tele-badge.svg)](https://t.me/DamarGPTbot)  [![Open In Collab](https://raw.githubusercontent.com/Damarcreative/TeleBot-GPT/674fe7fea86dd29e8b66b3d9069d2ff4f501cac0/badge/git-badge.svg)](https://github.com/Damarcreative)

### Library
- openai
- telebot
```sh
pip install openai 
pip install telebot
```

>If running the program and the prompt says error on line four, then:
delete in library "telebot"
and install library with "pyTelegramBotAPI"
Make sure you have added the API key before running

with the following command:
```sh
pip uninstall telebot
pip install pyTelegramBotAPI  
```

### API Key
You need an API key from open ai as a protocol to communicate with Open AI GPT
Example:
```sh
openai.api_key = "API_KEY"
```
And you also need the API key from telegram so that bots in telegram can communicate with this program code

```sh
api = 'API_KEY'
bot = telebot.TeleBot(api)
```
.
### RUN
If bash or shell says "bot started running" then it means bot has been running and you can communicate with GPT Chat via Telegram Chat.
