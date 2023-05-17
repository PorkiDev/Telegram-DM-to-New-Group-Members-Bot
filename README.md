![alt text](https://github.com/PorkiDev/Telegram-DM-to-New-Group-Members-Bot/blob/main/frm.png?raw=true)

![](https://komarev.com/ghpvc/?username=PorkiDev)
# **Telegram DM to New Group Members Bot**

This repository contains a bot that automatically sends messages to new members in any Telegram group as soon as they join. Remarkably, it does this without needing admin permissions. The tool is implemented in Python and utilizes the Telegram API.

## 📁 **Files Included**
- `setup.py`: This file helps you set up the necessary credentials to access the Telegram API.
- `scraper.py`: This file is responsible for continuously scraping new member data from the group.
- `send.py`: This file handles sending direct messages to the new group members.

## 🛠️ **Installation Guide**

1. To begin with, you need to have a Telegram API and hash. These can be obtained easily from [here](https://my.telegram.org/auth?to=apps).
2. After obtaining the necessary API details, provide them by running `setup.py` in your terminal using the command: 
   ```shell
   python3 setup.py
3. Now, you need to run scraper.py and send.py simultaneously. You can do this by splitting your terminal (if you're using a tool like Visual Studio Code, this can be done easily).
4. That's it! The bot is now set up and will run automatically.

## ⭐ **Features**
1. Checks new_members.csv every second for updates.
2. Introduces a delay between sending messages to each new member to prevent spamming and possible account restrictions.
3. Searches for new members every 60 seconds.
4. Tracks users to whom messages have already been sent, ensuring no duplicate messages are sent.
5. Checks if the username is valid and has not been messaged yet, ensuring efficient and accurate messaging.

## **Contact me**
Selling this for only 0.2 BNB
Telegram: @PorkiDev


Please note that the bot should be used responsibly and in accordance with Telegram's terms of service. The creators are not responsible for any misuse of this tool.
