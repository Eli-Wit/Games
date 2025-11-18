Python Games Collection

This repository contains several small Python games and experiments. These were originally written as personal learning projects and now serve as simple examples of game logic, input handling, and basic hardware interaction. The repository includes three Python games and several text files used as word banks.

**Black Jack.py**
A terminal-based blackjack game where the player faces the dealer.
Features include card drawing, hit or stay choices, automatic ace value adjustment, dealer rules, deck shuffling, and replay support. This script demonstrates basic game flow and input validation.

**Hangman.py**
A hangman game that allows the player to choose from multiple categories: US states, countries, or baby animals.
Features include difficulty selection, ASCII gallows drawings that update as lives are lost, prevention of repeated guesses, word list loading from text files, and a full replay loop. The game uses Animals.txt, Countries.txt, and US States.txt as its data sources.

**Padiddle.py**
A hardware-based game written for a Raspberry Pi. It uses GPIO buttons, LEDs, and a 16x2 I2C LCD display.
Features include two-player scoring, LED animations, a startup sequence, tie and win indicators, and both reset and shutdown triggers when both buttons are held. This script demonstrates hardware interaction, GPIO event detection, LCD output, and embedded-style game logic.
This game will only run on a Raspberry Pi.

**Animals.txt, Countries.txt, US States.txt**
These files are simple lists of line-separated words used by Hangman.py for its categories.

**Running the Games**

Blackjack and Hangman can be run on any system with Python:

python "Black Jack.py"
python Hangman.py

Padiddle requires a Raspberry Pi, proper wiring, and the following dependencies:

pip install rpi_lcd RPi.GPIO

Run with:

sudo python Padiddle.py

**License**

These games may be used for learning or experimentation.
