# lets play hangman
 **Command line interface based Hangman game using basics of python programming language**
 ### files contained: 2, i.e. word.py and hangman.py
 * `word.py` is a python file consisting of collection of words ranging from 3 to 13 letters.
 * `hangman.py` is a python file consisting of the game code.
 ## working of the code:
 1) importing random word from `word.py` file per game
 2) converting randomly choosen word into uppercase using **'get_word'** function
 3) displaying 'dash' to guess the correct word by mutliplying '__' with the length of the word
 4) setting 'guess' variable to false and 'tries' to 6 as the hangman consists of a head, a torso, 2 hands and 2 legs
 5) the **'play'** function uses loops like while, nested if else and for to check whether the letter guessed by the player is correct or not and displaying messages accordingly
 6) for example, decrement in 'tries' variable is made each player guessed a wrong letter or word and storing that wrongly guessed letter or word for future reference
 7) as the game proceeds, the stages of hangman is displayed using **'display_hangman'** function accordingly to the player's guesses; intial stage being only the gallow and final stage being the full hanged man
 8) also messages are also being displayed while proceeding in the game like _"Congrats, you guessed the word! You win!"_ if the player won the game or _"Sorry, you ran out of tries. The word was " + word + ". Maybe next time!"_ if the player lost the game with the correct word failed to guess by the player
 9) in **'main'** function, the **'get_word'** and **'play'** function is called and lastly asking the player if they wants to continue playing the game after a game is completed or not
 ## flowchart explaining how the game works:
 ![hangman flowchart](https://user-images.githubusercontent.com/87925162/192241538-76af402f-0a5d-4935-83eb-b8460717bd2c.png)

 
