# file-explorer-open-while-windows-installation-with-cmd

Method 1: Open File Explorer from Windows Setup
Boot from Windows USB.
On the first setup screen (Language selection), press:

Shift + F10 (opens CMD)

Type:
explorer.exe
Press Enter

Windows File Explorer will open (GUI).

Method 2: Use Open Dialog (without Explorer)
Press Shift + F10
Type:
notepad
In Notepad:
Click File
Click Open
Change "File type" to All Files
Browse drives and folders graphically

You can copy/paste files from here.

Method 3: From Repair Mode GUI
Boot Windows USB
Click Repair your computer
Go:

Troubleshoot → Advanced options → Command Prompt

Then type:

explorer.exe

Note: During normal Windows installation, File Explorer is not loaded by default, so you need to launch it manually.
