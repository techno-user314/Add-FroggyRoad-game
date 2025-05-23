This utility adds a screensaver to your Thumby Color.

When in the main menu, the screensaver will activate after 120 seconds of inactivity. Pressing any button will close it.
Note that button presses are not (currently) disabled when the screensaver is active, so pressing A to hide it may unintentionally launch a game.

IF YOUR DEVICE CANNOT START AFTER INSTALLATION, DELETE AND REPLACE THE FOLLOWING FILE WITH THE OFFICIAL UNMODIFIED VERSION:
/system/launcher/launcher.py

This installer works by inserting extra lines of code into the launcher file, as well as adding an extra file located at: /system/launcher/screensaver.py
By doing it this way, it should be possible to install even if the file has been updated or customized to an extent.
While this is done carefully, it is possible that a future or modified version of the launcher will break compatibility in a way the installer doesn't catch, which may prevent the launcher from starting. As stated above, you will need to manually replace the launcher file if this happens.

Editors like Thonny will usually prevent the screensaver from showing, as they need to interrupt the system to access files.
If you are connected to an editor, it is recommended to sent a Ctrl+D in the console any time you don't need to access files - This will reboot the device and allow the screensaver to run again.