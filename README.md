# INST126-1018-Hangman
Hangman completed for the first unit of the INST126 course at UMD.

## Introduction
This Hangman game features is a harder iteration of the widely beloved original Hangman game. The functionality and gameplay is entirely the same, but with a twist - the words are drawn from a bank of encrypted words. Users have a maximum of ten incorrect guesses before it's gameover - do you have what it takes?

## Installation
Prerequisites for running the program include JuptyerLab, with which it was made. Run the ipynb file in JupyterLab; more specifically, once the program is open, run the "start_game" cell by clicking on it and pressing "shift + return/enter."

## Instructions
Run the program (see "Installation" above).

The interface of the program is as follows:

**Current word: '_', '_', '_', '_'
You have 10 lives and you have used these letters: 
Please enter a letter:**

Every round of the program randomly selects an encrypted word form the bank. The "Current word" line will have as many _ (spaces) as the selected word has letters. 

When prompted by "Please enter a letter: ", please input a first guess. If the guessed letter is in the word, "Current word" will update and replace a _ with the letter. If the guessed letter is incorrect, one life is subtracted from the total and the counter is updated; consequently, the "you have used these letters: " sector updates to include the incorrect letter. (Don't worry! The same wrong letter will not be counted twice with regards to subtracting lives.) Then, the prompt for the next letter will appear.

If the user guesses all of the letters of the word, the decrypter will be employed and the real word will be revealed. If the lives counter reaches 0 first, the game is over! 

## Troubleshooting
Please keep in mind that as the files were created in JupyterLab, individual cells are not affected by common commands like "quit" or "exit," and therefore implementation of try-catches to prevent TypeErrors based on user input could not be done. Please enter each letter individually (e.g., 'A', 'B', etc.) as opposed to phonetically or in any other form.

If there are any unresolved issues with the program, please contact me at: aweng@terpmail.umd.edu
