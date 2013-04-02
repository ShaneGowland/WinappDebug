WinappDebug
===========

.NET debugger for CCleaner's winapp.ini entries

===========

Thanks to help from Robbie Ward (User: winapp2.ini); I've made this very simple console app to detect common errors with your winapp2.ini file.

How do I use it?
Simply place 'winapp2.ini' in the same folder as 'WinappDebug.exe' and run the tool. It will output a list of errors that it detects.

What kind of errors does it detect?
- Starting and trailing whitespace
- LangSecRef, FileKey & RegKey spelling errors
- Spaces in environmental variables
- Missing numbers next to FileKey and Regkey entries
- Missing backslashes next to environmental variables
- Incorrect usage of the 'Detect' & 'DetectFile' commands. 
