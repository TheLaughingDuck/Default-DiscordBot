# Default-DiscordBot

## Introduction and Purpose
A clonable repository that can be used as a starting point for new discord bot projects. This repo contains my own instructions or "modus operandi", and might not work for you. Follow the instructions under "Getting started" below to get started.


## Getting started
* Start by forking this repository.
    - Rename and change the description of the new repository.
    - Clone the repository into a suitable local folder with git (for example with Github Desktop).
    - Remove the "#" from the .gitignore file. (This will prevent changes in your .environ file from being uploaded. That would be VERY bad)

* Go to the discord developer portal. Go to "applications", and create a "New application".
    - Choose a name and provide a short description of your project.
    - Choose the proper intentions for your bot (for example enable reading messages).
    - Grab your bot token, and put it into your .environ file. Formatting should be:

        KEY1 = 12345
    - Invite the bot to a server (preferably a test server).

* Launching the bot:
    - Enable the client.run() command at the bottom of main.py.
    - Try running the bot.

* Hosting the bot
