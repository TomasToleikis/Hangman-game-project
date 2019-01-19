# Hangman game project
A final project by Tomas Toleikis for Vilnius School Of AI / class D.
This is a classic Hangman game, made in Google Colab.

The game takes a random word from the hangman_words.txt and invites a player to guess it by displaying underlines indicating the nr of letters in the word.
When the letter guessed is correct, the letter is displayed in the line of underlines.
When the quess is wrong, the symbol art of gallows is displayed - creating a hangman with each miss (6 misses untill game over).
There are 2 mode of game: 
- GALLOWS, which displays gallows symbol with a hangman forming in it (this mode allows 6 mistakes).
- CHRISTMAS TREE, which displays Christmas tree symbol with toys disapearing from it (this mode allows 7 mistakes).

At the beginning the game provides a hint - another random word and indicates how many common letters the words share.

# Requirements
The file must be opened in Google Colab.
The list of words is inluded as a hangman_words.txt. There is a separate cell at the begining that imports the file for game to use.

THE FILE IMPORTING CELL MUST BE RAN BEFORE PLAYING THE GAME.
