# SCPSL-server-status-discord
A discord bot that shows the player count and other info on your SCP:SL server

# Installation
Make sure you have NodeJS installed on your host machine.

First, download the source code for the bot above. Be sure to have made a bot on the Developer page of Discord (https://discord.com/developers/applications)

Next, take your server's IP and Port (eg 111.111.111:1111) and convert it to a MD5 hash. You can use https://www.md5hashgenerator.com/ to do so.
We do this so that the WebAPI will recognize the server and fetch correct JSON data.

Then, unzip your source files to a folder, and navigate:
Main Folder > Data > settings.json
Simply paste your bot token and client token in the respective areas.

Next, go to:
Main Folder > Data > events.json
Paste your hashed IP in the labeled area.

Invite the bot to your server, and make a channel "#server", and a role "Member", which must be given to everyone manually
Each time the bot is run, the channel is remade, so that no messages remain
Simply run the bot using "node bot.js" in the main folder via command prompt.

