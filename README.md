# Patch-Creator

A little tool to create patch titles in Jamf's Title Editor
NOTE: This will not work with Applications located in /System/Applications or any other location besides /Applications

This tool makes use of this great script from here:
https://github.com/brysontyrrell/Patch-Starter-Script


To use this tool make sure to enable full disk access first in System Preferences
Then open pick a application you want to create a patch title for and it will output two files.
.json file and .sh file for the Jamf extension attribute
Then open the Title Editor from the Jamf Pro console and pick import and upload the .json file and add the sh as the extension attribute if needed.
