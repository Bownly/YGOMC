I'm too lazy to type up a step by step explanation for the process. Sorry. But hopefully these bullet points are enough to get you started.

- Cartographer was used (via Cartographer/ygo_commands.txt" to extract the Japanese text from a clean Japanese rom file named "Yu-Gi-Oh! Monster Capsule GB.gb". The Cartographer.exe file was placed directly inside Cartographer/.

- Those output files were copy/pasted into Atlas1.11/scripts/, and renamed into something more user friendly.

- The patch.bat file assumes a modified rom file with English characters and a few misc modified bytes named "Yu-Gi-Oh! Monster Capsule GB eng font.gb".

- The Altas.exe file was placed directly inside Atlas1.11/.

- The notes.txt file in the root directory has a lot of helpful info on addresses and which bytes I changed for misc stuff like increasing text box sizes and changing offsets for the cutsenes' text addresses.

- I used Tile Molester for editing the font, hence the files inside Tiles/.