This project basically just lets you play flappy bird on an esp32 (and potentionally other Micropython-compatible devices) through an HT16K33_8X8 dot matrix display.

Files included:
1. typings folder: This includes a copy of [micropython stubs](https://pypi.org/project/micropython-esp32-stubs/), basically just letting VSCode do hints, auto-complete and type checking for Micropython-exclusive libraries without having to add the libraries themselves into the repository
2. ht16k33.py and ht16k33matrix.py: libraries for the dot-matrix display, which I got from keystudios' files.
3. test.py: A test version of it that prints to the terminal and uses input instead of a button for jumping
4. main.py: The main file for the code
