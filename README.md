Download ILSpy if you have not already done so. Place it on the desktop and extract it.
Run ILSpy. Choose File, then Open. Navigate to your Steam's Terraria folder, which is usually located in C:\Program Files (x86)\Steam\SteamApps\Common\Terraria\ and choose a file to decompile:
Original game (no mods): Terraria.exe
Original game (with tConfig): TerrariaOriginalBackup.exe
tConfig: tConfig.exe
Regardless of what you have selected, it will generate a file tree, previewing what it has to do. After this, choose File, then Save Code. Choose a directory to save the code to.
ILSpy will then reverse-engineer the game into a few dozen C# files in the chosen directory, and it will also conveniently generate a project file if you use Visual Studio.
Please note: This process will take some time, so be patient! On a modern, high quality computer, it will take about 10 minutes. If your machine is a bit older, then it could take up 30 minutes or more!
After ILSpy has finished running, you should have a number of C# files in the folder you chose.
