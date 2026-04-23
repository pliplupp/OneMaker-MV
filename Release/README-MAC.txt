For whatever reason, at least on ARM macs, Onemaker will only work if hijack.rcc is in your user folder, in addition to the folder inside of RPG Maker.

To install: 
Unzip QtCore
Put the QtCore.Framework folder inside of (RPG MAKER INSTALL DIR)/RPG Maker MV.app/Contents/Frameworks
Copy _hijack_root and hijack.rcc to (RPG MAKER INSTALL DIR)/RPG Maker MV.app/Contents/MacOS
Copy hijack.rcc to your user directory
Run sudo xattr -rc "RPG Maker MV.app" in the directory RPG Maker is installed in, just to remove possible MacOS quarantine stuff.

If everything is done correctly, Onemaker should work.
