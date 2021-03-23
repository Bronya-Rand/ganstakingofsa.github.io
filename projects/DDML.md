## Doki Doki Mod Launcher (DDML)

Doki Doki Mod Launcher is a mod launcher for the visual novel "Doki Doki Literature Club" that allows players to install Doki Doki Literature Club mods with ease using the Ren'Py Source Distribution Kit (SDK).
> This project is unafilliated with either Team Salvato or RenpyTom. See the [disclaimer](../information/disclaimer/disclaimer.md) page for more information.

## Features
- Support for Ren'Py 7.4.2 Mod Installation
- Automatic DDLC Installation
- Automatic Mod Installation
- Dark Mode based off One UI from "True Reality".
- SHA256 Checking for DDLC ZIP files and folders to verify authenticity.

## Note
For Linux, make sure either `gtk`, `tk` or `python-tk` is installed on your system along with Python 2.7.18. MacOS will need to download CLI tools before running DDML due to `python3` not being available on Mac till requested.

## Changes

Version 5.2.2 - The "Better-ish" 7.4 One **(Current)**
- Fixed syntax issues
- Lowered file size
- Fixed a bug that may cause ZIPs under the name `Renpy7Mod` to not be recognized.

Version 5.2.0 - The 7.4 One **(Last Version)**
- Updated SDK to 7.4
- Dark Mode
- Fixed a bug where folder extraction in MacOS may be improperly extracted.
- Changed a setting where ZIP location resets if the browser extract response is changed. (DDML for Mac)
- Fixed a bug where some Mac OS copies are unable to boot
- Fixed a bug where the DD Mod Club mod list won't load.
- Fixed text formatting in Settings
- Fixed some settings that should appear on both Windows and Linux.

For other version changes, refer to the [release](https://github.com/GanstaKingofSA/DDML/releases) section of the DDML Github repository.

