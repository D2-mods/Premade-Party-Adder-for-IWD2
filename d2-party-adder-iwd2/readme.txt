Premade Party Adder (for IWD2)
Github: https://github.com/D2-mods/Premade-Party-Adder-for-IWD2
Installs on: Icewind Dale 2


==================================================
Overview
==================================================
Adds up to 5 premade parties to the party selection screen, including character info and customizable desciptions. 
There's also an option to remove the existing parties.

NOTE: Currently, the party info will only show unmodded Skill/Feat names.


==================================================
Installation
==================================================
- Place up to 6 CHR files in one of the party folders
- Optional: Add biography and/or portrait files to the folder
- Run the installer
- Each party is a separate component and CHR files are added to the Characters folder
	
Optional: 
- Biographies will also be added. These are just text files with the .RES extension. They must have the same filename as the CHR file. Characters without a RES file will instead get the generic biography used for Black Pits 2, with the addition of their name.
- Portraits in the folder will be copied to the override (though not made selectable at character creation).


==================================================
Customizable descriptions
==================================================
- You can edit the party name and description text by editing the "customize" files in each party folder. IWD2 uses two descriptions, one above and one below the character stats. Each description must be a single line or paragraph without breaks, but they can be as long or short as you want.
- I also included some basic starter info as default text if you choose not to customize the desciptions.


==================================================
Additional info
==================================================
- Characters are added in number/alphabetical order. If there are more than 6 CHR files in the folder, only the first 6 are added to the party, though all will be copied to the Characters folder and can be imported.


==================================================
CREDITS
==================================================
Modder: Dan_P

Tools and Resources used:
- WeiDU (https://github.com/WeiDUorg/weidu)
- NearInfinity (https://github.com/Argent77/NearInfinity)
- Notepad++ (https://notepad-plus-plus.org/)
- Git Bash (https://git-scm.com/downloads)
- Infinity Auto Packager (https://github.com/InfinityTools/InfinityAutoPackager)
- IESDP (https://gibberlings3.github.io/iesdp/main.htm)
- LibIconv for Windows (http://gnuwin32.sourceforge.net/packages/libiconv.htm)


==================================================
Version info
==================================================
v1.3
- "Empty party selection list" has 2 subcomponents now, so it won't be automatically installed if choosing "Install all components".

v1.2
- The "Empty the party selection list" option will now be skipped if any custom parties from this mod are installed.
- Party components will fail to install if no CHR files are in the folder. This won't give a WeiDU error. It'll just say "INSTALLATION ABORTED". If using a mod manager, installation will continue uninterrupted.

v1.1
- changed backup folder to weidu_external
- added HANDLE_CHARSETS function
- changed to be able to install/uninstall all at once

v1.0 - release version
v0.4 - minor fixes/adjustments
v0.3 - added text for skills and feats
v0.2 - done, except skills and feats
v0.1 - split off from IWDEE version