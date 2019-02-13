# Word-Guess-Game

https://silvershan.github.io/Word-Guess-Game/

Problem addressed: to create a game of hangman that allowed any key to be pressed for the game to begin.  The user was allowed 10 guesses - no letters could be guessed more than once -  and if they did not guess the correct word within 10 guesses, 1 point was added to the "losses" category.  If they were able to guess it within the 10 guesses, 1 point was added to the "wins" category.

How solved: Incorporated JavaScript for the entire functionality of the game.  HTML and CSS was used for the user interface and ability to play the game coded through JavaScript.

Technical approach:  I began by coding the HTML and created divs that I could use to call out in Javascript.  Next came coding the JavaScript.  The number of wins and losses was set to 0 to begin the game and I created an array of all of the possible letters to guess (A-Z).  I then created an array of all of the words I wanted the hangman game to cycle through and set it up so these words would randomly be chosen when the user began the game.  I then coded the correct vs. incorrect guesses so the user would know if they had guessed the correct letter or not.  After the entire game was coded, the final step was adding the CSS so it would be more attractive to the user.
