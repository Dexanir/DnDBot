# DnDBot
This is a Telegram bot for playing Dungeons and Dragons made by theepicflyer. I'm just trying to fix it (new tg API, new python3, etc).

## Installation
Download files from `main` folder
The bot uses the [Python Telegram Bot](https://github.com/python-telegram-bot/python-telegram-bot)
Install it with `pip install python-telegram-bot`

## Setup
1. `main.py` in the `main` folder will be the only file someday.
2. Get your own bot and token from [Telegram](https://core.telegram.org/bots)
3. Replace `TOKEN` with your own token
4. Add your bot to a group with your players
5. Run `main`



## Player Commands:
Command | Action
--- | --- 
/start | starts the DnD bot
/createcharacter [character name] | Use this command and follow the prompts to create a new character
/printcharacterstats [character name] | Prints a character's stats, add the name of the chharacter after the command
/help | Open this help message
/roll[int] | Rolls a dice with the customisable maximum value

## Dungeon Master Commands:
Command | Action
--- | --- 
/createmonster [monster name] [health points] | Creates a monster.
/attackmonster [monster name] [damage] | Reduces health of the monster by a given number.
/changexp [character name] +/- X | Adds or subtracts a certain amount of health from a character.
/changegold [character name] +/- X | Adds or subtracts a certain amount of gold from a character.
/changehealth [character name] +/- X | Adds or subtacts a certain amount of health from a character.
/inventoryupdate [character name] add/remove [item] [no. of item] | Adds or removes a certain amount of a specific item from a character's inventory.
/printinventory | Current state of the inventory.
