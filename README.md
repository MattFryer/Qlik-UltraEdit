#QlikView Language Definition for UltraEdit

The QlikView Custom Language Definition for UltraEdit gives basic syntax highlighting and auto-completion when working with QlikView script files in UltraEdit.

The syntax highlighting that is provided is limited to the capabilities of UltraEdit Wordfiles and is an approximation of what you would get in QlikView's Edit Script dialog. It currently supports the following features:

* Highlighting of all current (v11.20) functions
* Highlighting of all current (v11.20) keywords and statements
* Highlighting of line comments (//) and block comments (/* */) 
* Folding of code blocks including IF, SWITCH, FOR, DO and SUB statements
* Load statements and subroutines shown in the UltraEdit function list

If you find any keywords or functions missing then please let me know by logging an issue and I'll add them to the next release. Support may also be added for subroutines within QlikView code libraries. If you'd like me to add support for your library, again please contact me.


##Installation

Here are the steps to getting it installed and working yourself:

1. It is recommended that you are running the latest version of UltraEdit. Some previous versions to not support all Wordfile features.
2. Close all running instances of UltraEdit.
3. Download the QlikView Wordfile ZIP archive file from https://github.com/MattFryer/QlikView-UltrEdit/archive/master.zip
4. Unpack the 2 files from the archive to a folder on you hard drive.
5. Copy the "qlikview.uew" file from the folder to the "%UserProfile%\AppData\Roaming\IDMComp\UltraEdit\wordfiles\". Tip: you can copy the path (including the % part) into Windows Explorer address bar. Windows may ask you to provide administrator privileges.
6. Open UltraEdit and navigate to the menu Advanced -> Configuration...
7. The Configuration dialog will appear, under the "Navigation" tree on the left hand side, select Editor -> Word Wrap/Tab Settings.
8. Click the "Change list..." button (top right), the Modify File Types dialog will appear.
9. Type "qvs" into the File Extensions box and click "Add". Now click "OK" to close the dialog.
10. Back on the Configuration dialog, from the "Select extension for settings or default" drop-down select the "qvs" entry you just added.
11. Click the "Browse..." button and navigate to the "AutoComplete.txt" you unpacked from the ZIP file in step 4 above. Click "Open".
12. Click "OK" to close the Configuration dialog.


##Upgrade

If you already have a previous version of the QlikView Wordfile installed you will need to follow these steps to remove it and install the latest version:

1. Close all running instances of UltraEdit.
2. Download the QlikView Wordfile ZIP archive file from https://github.com/MattFryer/QlikView-UltrEdit/archive/master.zip
3. Unpack the 2 files from the archive to a folder on you hard drive.
4. Copy the "qlikview.uew" file from the folder to the "%UserProfile%\AppData\Roaming\IDMComp\UltraEdit\wordfiles\" and if prompted, allow it to overwrite any existing version of the file. Tip: you can copy the path (including the % part) into Windows Explorer address bar. Windows may also ask you to provide administrator privileges.
5. Open UltraEdit and navigate to the menu Advanced -> Configuration...
6. The Configuration dialog will appear, under the "Navigation" tree on the left hand side, select Editor -> Word Wrap/Tab Settings.
7. From the "Select extension for settings or default" drop-down select the "qvs" entry. If no "qvs" entry is shown, continue from point 8 of the Installation instructions above.
8. Click the "Browse..." button and navigate to the "AutoComplete.txt" you unpacked from the ZIP file in step 4 above. Click "Open".
9. Click "OK" to close the Configuration dialog.


##How To Use

If you open a .qvs file, UltraEdit will automatically identify it as a QlikView script file and apply the Wordfile for you. If you are creating a new file or using a different file extension then you'll need to change the language using the menu  View -> View as (Highlighted File Type) -> QlikView.


##Disclaimer

This Wordfile is provided free of charge, as is, with no warranties or guarantees. Neither Datoniq Limited or QlikViewAddict.com (including any of it's contributors) accept any liability for problems or loss resulting from it's use. 