# NotepadWithoutDevChannel
Get the new Notepad on any Windows 11 build.

![Notepad (Preview) on build 22000](https://i.imgur.com/FWOXddh.jpg)
# Installation
## Getting the AppxManifest file
First, download the code as a ZIP file by clicking the green "Code" button and saving as a ZIP. Extract it to someplace you will remember. Open the extracted folder and find the AppxManifest file. Once you find it, click it. Then press the Shift key while right-clicking to bring up the Extended Context Menu. Click "Copy as path" from the menu.
## Enabling Sideloading
Open Settings and click "Privacy & security". Then, under "Security", click the "For developers" option with the screwdriver and wrench icon next to it. Set the "Developer mode" toggle to on.  Click "Yes" at the prompt, and close out of Settings.
## Sideloading with PowerShell
Press the Windows and R keys at the same time to open Run. Type "powershell" and press Enter. In the PowerShell window, type `Add-AppxPackage -Path FILEPATH -Register`. **Be sure to use Ctrl+V to paste your AppxManifest file path instead of typing "FILEPATH".** If you did the steps correctly, Notepad should install and will be found in your Start Menu.
