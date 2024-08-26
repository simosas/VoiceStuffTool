# VoiceStuffTool
A tool for getting Baldur's Gate 3 character voicelines


Download the VoiceStuffTool.rar file and unzip it. The program itself is VoiceStuffTool\bin\Debug\VoiceStuffTool.exe

The .rar also contains the entire source code for the program. Due to GitHub size limits I could not just upload them as files.

Usage:

1. Run VoiceStufftool.exe

2. Wait for the setup to finish (you will be prompted to enter a character name)

3. Enter the name of the character you want to get voicelines of. Make sure that the name is accurate, e.g. inputting "Glut" will result in character not being found, because the actual name is "Sovereign Glut".

4. If the name is valid, the process will begin. For characters with a lot of voicelines, it can take up to a minute.

5. The results will appear in VoiceStuffTool\bin\Debug\Results.


The program may not have 100% accuracy on all voicelines. This is because some voicelines are not defined the same way others are, so it basically just guesses which files might actually be accurate.

You will get a warning if the chosen character has point and click or spell cast voicelines. Those are defined together with other voicelines, however the game uses a completely different file for them, so the output may be inaccurate.

The program will attempt to guess which files might be the "real" ones, those will appear as "potential extra matches" in the character filenames file.



