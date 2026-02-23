# LNKLauncher
Simple command launcher for EPIC games or just Windows links (Windows)
# WHAT'S THIS FOR?
This simple command tool allows you to launch EPIC games from Steam/GOG (or in general any .url and .lnk Windows files). It will not open any temporary window to launch the app. You can optionally specify also the real taskname launched by the game, and wait 'till it actually quits (so Steam/GOG etc. will show you're still playing 'till you really quit the game).

# FAQ
Q: can I use additional launcher parameters to launch f.e. "game.exe -fullscreen"?\
A: yes, it should work

# ARGUMENTS
LNKLauncher.exe <PathToLNK> [ProcessName.exe] [optional parameters...]

# EXAMPLE
You want to add GameX from EPIC to your Steam or GOG library...

1) create an icon on your desktop for that game (Steam, GOG, EPIC... they all have an option to do that from the client itself)
2) move that icon (usually a .url) into your game root directory (e.g. C:\Epic Games\Games\GameX\)
3) as launch option from Steam for example use:
   - PATH:  "C:\Users\me\Util\LNKLauncher.exe"
   - START FROM:  "C:\Epic Games\Games\GameX\"
   - START OPTIONS:  "C:\Epic Games\Games\GameX\GameX.url" "gameX.exe" -optional_parameters_here

This will launch your EPIC game (or any other Windows .url/.lnk) exactly as if you doube-clicked on the client generated game launch icon.\
Will also wait for the task to quit to show you're still playing the game, 'till you actually quit.

Enjoy!
