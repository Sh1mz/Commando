# Commando
[![Discord](https://discordapp.com/api/guilds/222078108977594368/embed.png)](https://discord.gg/bRCvFy9)
[![Downloads](https://img.shields.io/npm/dt/discord.js-commando.svg)](https://www.npmjs.com/package/discord.js-commando)
[![Version](https://img.shields.io/npm/v/discord.js-commando.svg)](https://www.npmjs.com/package/discord.js-commando)
[![Dependency status](https://david-dm.org/discordjs/Commando.svg)](https://david-dm.org/discordjs/Commando)
[![Build status](https://travis-ci.org/discordjs/Commando.svg)](https://travis-ci.org/discordjs/Commando)

## About
I forked this from Commando so I  could remove the default commands, since for some reason disabling them in registerDefaultcommands wasn't working for me.

Commando is the official command framework for [discord.js](https://github.com/discordjs/discord.js).
It is flexible, fully object-oriented, easy to use, and makes it trivial to create your own powerful commands.
Additionally, it makes full use of ES2017's `async`/`await` functionality for clear, concise code that is simple to write and easy to comprehend.

## Features
- Plain command names and aliases
- Regular expression triggers
- Robust parsing of arguments (with "quoted strings" support)
- Sophisticated argument system (optional)
	* Automatic prompting for arguments that aren't provided
	* Type system with rules, automatic validation, and parsing to usable values
		- Basic types (string, integer, float, boolean)
		- Discord objects (user, member, role, channel, message)
		- User-defined custom types
		- Union types
	* Automatic re-prompting of invalid arguments
	* Optional arguments with default values
	* Infinite arguments (arguments that accept as many values as provided)
- Multiple responses to commands
- Command editing (user edits their message that triggered the command, and the bot's response updates with it)
- Command reloading, as well as loading/unloading
- Command throttling/cooldowns

## Installation
**Node 8.6.0 or newer is required.**  
`npm install discord.js-commando`

## Documentation
[View the docs here.](https://discord.js.org/#/docs/commando)  
See the [discord.js documentation](https://discord.js.org/#/docs) as well.
