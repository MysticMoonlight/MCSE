MysticConfig: Source Edition
===========
MysticConfig: Source Edition is the script compilation which aims to support all source engine games.

## Features ##
This script has lack of scripts due to compatiability with other source engine mod. Feel free to make feedback on issue tracker!
- **Auto Crouch-Jump:** Automatically makes you crouch-jump when playing the spacebar. 
- **Netgraph:** displays the netgraph on the score screen (`Tab` key).
- **Null-Cancelling Movement Script:** a classic script which lets you immediately change direction. As of v4 "Carbon", now you can select keyboard types on `_settings.cfg` file.
- **Suicide Key:** kills yourself at the touch of a `Delete` key. Note: kill command may not work on some games.
- **Viewmodel Toggling:** toggles display of the active weapon at the press of the `Insert` key.
- **Startup Message:** Startup message displays when you launch TF2. You can toggle them in settings file.
- **Help command:** Typing `mc_help` will now display list of commands.

## Settings ##
MC:SE comes with several settings used to toggle certain features; edit them in `cfg\_settings.cfg`:

- `AUTO_CROUCH_JUMP`
- `CLEAR_CONSOLE_ON_START`
- `NULL_CANCELLING_MODE`
- `SHOW_NETGRAPH`
- `SUICIDE_KEY`
- `STARTUP_MESSAGE`

## Installation Steps ##
### Normal Installation ###
1. Head to [release page](https://github.com/MysticMoonlight/MysticConfig-Source-Edition/releases) and click on MCSE.zip to download file
2. Extract the zip file (Recommend using with 7-zip for extraction)
3. locate your Source Engine Game(If CS:S, go cstrike) installation's `custom` folder (usually located at `C:\Program Files (x86)\Steam\SteamApps\common\Team Fortress 2\tf\custom` on Windows)
4. Move the extracted folder to custom folder.
5. Edit the settings on `_settings.cfg` to customize the config.
6. Launch TF2

## List of Supported/Unsupported Games ##
### Supported Games ###
Since MC:SE aims to support all source engine games, most source engine games should work without any issues.
* Team Fortress 2 (TF2 focused version is also available below, named MysticConfig)
* Counter Strike: Source
* Half-Life 2 Series (Half-Life 2, Half-Life 2: Episode One, Half-Life 2: Episode Two, Half-Life 2: Lost Coast)
* Half-Life: Source
* Black Mesa
* Obsidian Conflict (Installation may differ than other source engine games)
* Portal
* Portal 2
* No More Room in Hell
* Zombie Panic! Source
* And many more Source Engine games which supports custom folder

### Unsupported Games ###
* Left 4 Dead series (It uses addon system and does not support folder based mods)
* Counter Strike: Global Offensive (Valve removed custom folder support)
* Any GoldSrc/Source 2 Engine games (This script compilation was not meant to support GoldSrc and Source 2 Engines)

## Credits ##
The scripts bundled together would not have been possibly were it not for the scripts and tutorials provided by the following people:

- [Lyrositor](https://github.com/Lyrositor) for [TF2 Script Collection](https://github.com/Lyrositor/TF2-Scripts),
- [JarateKing](https://github.com/JarateKing) for [jarconfig](https://github.com/JarateKing/jarconfig),
- mastercoms for [mastercomfig](https://www.mastercomfig.com) mod,
- The [Team Fortress 2 Wiki](http://wiki.teamfortress.com) contributors for their scripting tutorials,
- [Zoolooman](http://wiki.teamfortress.com/wiki/User:Zoolooman) for his `echo` [tutorial](http://wiki.teamfortress.com/wiki/User:Zoolooman/Scripting),
- Chdata, Stabby Stabby for [Improved Crouch Jump Script](https://gamebanana.com/scripts/7982),
- povohat, Perkzitos for [Null-Cancelling Movement Script](https://gamebanana.com/scripts/9842).

If you are the author of this script and need to be in credit, or want your script to be removed, please let us know on our issue tracker.

## Related Projects ##
* [MysticConfig](https://github.com/MysticMoonlight/MysticConfig) - The TF2 Script collection, forked from Lyrositor's [TF2-Scripts](https://github.com/Lyrositor/TF2-Scripts)

## License ##
This project is licensed as MIT License. You are free to copy, modify, use the source code.

Source, Source logo, Valve Corporation, Valve Corporation logo are trademarks and/or registered trademarks of Valve Corporation. MysticConfig: Source Edition is not sponsored, endorsed, licensed by, or affiliated with Valve Corporation.