# tg_chat_logger
Telegram bot for chat logging

Requirements: telebot, python3. 

Installation:
1. Install the telebot library with the command sudo pip3 install telebot.
2. Get the API key from @BotFather for your bot, and paste it into the script (I marked where).
3. Use @BotFather to set permission for the bot to read messages in groups.
4. Run the bot locally, for example #python3 main.py


The bot logs messages by putting them into text files, from all chats where it is located. Text files are labeled with date and group name.

Separate files are made for service messages of visits and exits of users. 
