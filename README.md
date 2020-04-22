# BOTW Save Sync for Switch and CEMU (Wii U)

BOTW Save Sync is a work-in-progress version of DeltaJordan's [Breath of the Wild Save Manager](https://github.com/DeltaJordan/BotW-Save-Manager).

In it's current state, it can convert Switch <-> Wii U BotW <v1.5.0 save files.
I hope to add functionality where you can connect your Switch to your PC via USB or Wi-Fi, specify your CEMU's mlc01 folder and automatically sync your save in the direction specified (CEMU -> Switch or Switch -> CEMU).

Written with .Net Framework for Windows with UI, and .Net Core (command-line only) for cross-compatibility.

## Usage:

### Windows-only UI

1. Select File > Open save > The folder that contains "option.sav".
2. Click convert and wait for it to finish.
3. Click Browse to the folder you want to save it to, preferrably an empty folder.
4. Click Save and the application should write it to the folder.

### Cross-platform command-line

1. Enter the path of option.sav when prompted.
2. Wait for the files to convert.
3. Either select a folder for it to save to or press Enter to overwrite your save with the converted version.
4. Once it finishes you'll be good to go to copy it to your console.

## Dependencies:

* Windows
  * [.Net Framework 4.7](https://www.microsoft.com/en-us/download/details.aspx?id=55170)
* Other
  * .Net Core - varies by system

## Credits:

* A fork of [Breath of the Wild Save Manager](https://github.com/DeltaJordan/BotW-Save-Manager) by DeltaJordan
* Original command-line [save converter](https://github.com/WemI0/BOTW_SaveConv) by WemI0
* Some code taken from [BOTW savegame-editor](https://github.com/marcrobledo/savegame-editors/tree/master/zelda-botw) by marcrobledo
