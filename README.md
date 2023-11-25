# Discord Bot - Nirad

## Introduction

Nirad is a Discord bot designed to provide various functionalities and entertainment features in Discord servers. It includes features such as fetching Minecraft server status, playing music from YouTube, and responding to custom commands. 

## Features

### Minecraft Server Status

- Use the `.status` command to check the status of a Minecraft server.
- Use the `.ip` command to get the address of the Minecraft server.

### Music Commands

- Use the `+play` command to play music from YouTube.
- Use the `+skip` command to skip the currently playing song.
- Use the `+stop` command to stop the music playback.

### Custom Commands

- Responds to custom commands such as greetings and inquiries about Nirad's abilities.
- Example commands: `Hello`, `Nirad is`, `Is Nirad good at maths?`, `Is Nirad cute?`, and more.

### Pinning Server Status

- Automatically updates and pins the Minecraft server status in a specified channel.

### Configuration

- Customize the bot's behavior through the `config.json` file.
- Modify settings such as server address, server port, prefix, and more.

## Getting Started

1. Clone the repository.
2. Install the required Node.js modules using `npm install`.
3. Configure the `config.json` file with your Discord bot token and other settings.
4. Run the bot using `node your_bot_file_name.js`.

## Commands

- **Minecraft Server Status:**
  - `.status`: Check the status of the Minecraft server.
  - `.ip`: Get the address of the Minecraft server.

- **Music Commands:**
  - `+play`: Play music from YouTube.
  - `+skip`: Skip the currently playing song.
  - `+stop`: Stop the music playback.

- **Custom Commands:**
  - Responds to various custom commands based on user input.

- **Configuration Commands:**
  - `.set`: Update bot configuration settings.
  - `.force-update` or `.fu`: Force update server status channels.

- **Help Command:**
  - `.help`: Display a list of available bot commands.

## Notes

- The bot's prefix is set to `+`.
- Make sure to set up the `config.json` file with accurate information.

## Disclaimer

This bot is provided as-is, and its usage is subject to the terms and conditions set by Discord. The developers are not responsible for any misuse or issues that may arise from using this bot.
