# Disclaimer
I use this personally on any new system. This repos is pretty much only here so i can easily access the files. 
Feel free not to trust the installers posted in release, and build them yourself. 

# NoDeadKeys
Keyboard Layout without Dead Keys (avoid typing ^ twice)
https://superuser.com/a/280032

- Check the Releases page for the installer: https://github.com/SeidChr/NoDeadKeys/releases
- you may want to unblock the extracted files, so windows doesnt complain about installing

with powershell 6+ in your extracted zip folder:
```ps
  gci . -recurse | unblock-file
```

OR if you do not want to trust the installer, create one yourself:

- Install the Dotnet Framework 3.5 from you 'Windows Features'
- Find the Keyboard Layout Creator Tool here: https://www.microsoft.com/en-us/download/details.aspx?id=102134
- Load the .klc file
- Generate a setup for the layout
