# discord

## Purpose
Discord API wrapper for building bots and integrations with SageLang.

## Features
- **Client**: Core Discord gateway client.
- **Gateway**: Real-time event handling.
- **REST**: Interface for Discord REST API.

## Usage Example
```sage
import discord.client

let bot = DiscordClient(token)
bot.on_ready(proc(): print "Bot is ready!")
bot.connect()
```
