---
layout: post
tags: [Java, Java Swing]
---

<img src="assets/images/screenshot-nguess3.PNG" alt="screenshot of N-Guessing Game" style="width: 49%; display: inline;">
<img src="assets/images/screenshot-nguess.PNG" alt="screenshot of N-Guessing Game" style="width: 49%; display: inline;">
<hr/>

This challenging and logical game lets the player first decide how many digits they want to challenge. The program will generate a random number with that many digits. 
The player needs to guess the number using the hints from each guess. After correctly guessing the number, players can log their records, and records can be checked at any time.
The GUI is built with Java Swing. The user records are stored in Java Binary files locally.

### How To Play
Select how many digits the target is. Then start guessing with any number with that many digits. After each guess, feedback will be provided. 
The feedback includes "how many correct numbers in the guessed number in the correct place" and
"how many correct numbers in the guessed number in the incorrect place".

### Example:
If the correct answer is 1998. \
A guess of 0123 will have 0 perfect guess and 1 imperfect guess. \
A guess of 1111 will have 1 perfect guess and 0 imperfect guess. \
A guess of 9988 will have 2 perfect guesses and 1 imperfect guess.

[GitHub Link](https://github.com/allenLQVE/N-Guessing)