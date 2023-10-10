# What is this bot
 Bot to find unused Discord channels and send them messages to check if they are still in use 

# How to install and run 

 `python3 -m pip install -r requirements.txt`
 `python3 main.py`

# Prerequisites
* A Discord account
* Python installed on your computer

1. Create a Discord Bot & get Token:

Go to the Discord Developer Portal. https://discord.com/developers/applications
* Click "New Application" and give your bot a name.
* In the left sidebar, click "Bot" and then "Add Bot." This will create your bot user.
* Under the bot's username, click "Copy" to copy the bot's token. You'll have to fill it in the script.
* then ask the admin of the channel to add you by send him this link
  find client/APPLICATION ID at General Information tab

https://discord.com/oauth2/authorize?client_id={{ClientId}}&permissions=8&scope=bot%20applications.commands

* permissions 8 is admin you play with gui to find the number for more specific permissions
