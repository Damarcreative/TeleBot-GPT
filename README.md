# Documentation

[![Open In Collab](https://raw.githubusercontent.com/Damarcreative/TeleBot-GPT/674fe7fea86dd29e8b66b3d9069d2ff4f501cac0/badge/colab-badge.svg)](https://colab.research.google.com/drive/1p-6whVjMSoBcN9Rv0JbQDZiKDvAUNP0x)  [![Open In Collab](https://raw.githubusercontent.com/Damarcreative/TeleBot-GPT/674fe7fea86dd29e8b66b3d9069d2ff4f501cac0/badge/tele-badge.svg)](https://t.me/DamarGPTbot)  [![Open In Collab](https://raw.githubusercontent.com/Damarcreative/TeleBot-GPT/674fe7fea86dd29e8b66b3d9069d2ff4f501cac0/badge/git-badge.svg)](https://github.com/Damarcreative)
### Library
- openai
- telebot
```sh
pip install openai 
pip install telebot
```

>Jika mejalankan program dan promp mengatakan error pada barisan empat, maka:
hapus pada library "telebot"
dan pasang library dengan "pyTelegramBotAPI"
Pastikan sudah menambahkan kunci API sebelum menjalankan

dengan perintah berikut:
```sh
pip uninstall telebot
pip install pyTelegramBotAPI  
```

### Kunci API
kamu membutuhkan kunci API dari open ai sebagai protokol untuk berkomuniksi dengan Open AI GPT
Contoh:
```sh
openai.api_key = "sk-6frzPijQmfw********29A3jd4WT0LTS5qV"
```
dan kamu juga membutuhkan kunci API dari telegram agar bot di telegram dapat berkomunikasi dengan kode program ini

```sh
api = '12346788:AAGpXLK***********upBY1ISWjWrqTeI3erA23c'
bot = telebot.TeleBot(api)
```

### RUN
Jika bash atau shell mengatakan "bot start running" maka artinya Bot telah berjalan dan kamu sudah dapat berkomunikasi dengan Chat GPT melalui Chat Telegram
