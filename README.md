## RoundRestore
Useful Plugin for restoring Rounds in a competitive CS:GO Match.

### About this Plugin
- This is my first Sourcemod Plugin, so this is probably not perfectly programmed, I initially
 only created this Plugin to use it on my own Server because there was no Plugin to restore Rounds before.
- This Plugin only uses already existing CS:GO Server Commands to restore Rounds.
- If you want to change something in this Plugin, you are free to copy the code and compile it at [sourcemod.net](http://www.sourcemod.net/compiler.php)
- Of course you can always report bugs or propose changes here on github :)

### How to use:
1. Confirm you have [SourceMod](https://www.sourcemod.net/downloads.php) and [MetaMod:Source](https://metamodsource.net/downloads.php) running on your Server.
2. Download RestoreRound.smx from [releases](https://github.com/MoritzLoewenstein/RoundRestore/releases)
3. Move it to your csgo/addons/sourcemod/plugins directory
4. Make sure the plugin is running ("sm plugins list")
5. Make sure you set 
  `mp_backup_round_file_pattern %prefix%_round%round%.txt`
6. Use any of the Chat Commands down below

### Chat Commands
 To use any of these commands you need to be sourcemod admin
- !restore          Main Menu
- !restorelast      Displays vote for restoring last round

### Main Menu
- First Menu Item restores last round.
- Second Menu Item displays all rounds with the current round at the top (you can navigate back and forth)

#### Thanks for using this Plugin ~
