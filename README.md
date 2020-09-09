# WheelOfFortune
A mini game built with Python with human players and computer players.

This game is the project submission for one of the courses in Python 3 Programming Specialization available on Coursera.

Here are the rules of our game:

1. There are num_human human players and num_computer computer players. Every player has some amount of money ($0 at the start of the game)

2. Every player has a set of prizes (none at the start of the game)

3. The goal is to guess a phrase within a category. For example: Category: Artist & Song

    Phrase: Whitney Houstonâ€™s I Will Always Love You

    Players see the category and an obscured version of the phrase where every alphanumeric character in the phrase starts out as hidden (using underscores: _): Category:         Artist & Song

    Phrase: _______ ______' _ ____ ______ ____ ___

4. Note that case (capitalization) does not matter

5. During their turn, every player spins the wheel to determine a prize amount and: If the wheel lands on a cash square, players may do one of three actions: Guess any letter that hasnâ€™t been guessed by typing a letter (a-z) Vowels (a, e, i, o, u) cost $250 to guess and canâ€™t be guessed if the player doesnâ€™t have enough money. All other letters are â€œfreeâ€ to guess

          The player can guess any letter that hasnâ€™t been guessed and gets that cash amount for every time that letter appears in the phrase

          If there is a prize, the user also gets that prize (in addition to any prizes they already had)

          If the letter does appear in the phrase, the user keeps their turn. Otherwise, itâ€™s the next playerâ€™s turn

          Example: The user lands on $500 and guesses â€˜Wâ€™
          There are three Wâ€™s in the phrase, so the player wins $1500
          
     Guess the complete phrase by typing a phrase (anything over one character that isnâ€™t â€˜passâ€™)
          If they are correct, they win the game
          If they are incorrect, it is the next playerâ€™s turn

          Pass their turn by entering 'pass'
6. If the wheel lands on â€œlose a turnâ€, the player loses their turn and the game moves on to the next player

7. If the wheel lands on â€œbankruptâ€, the player loses their turn and loses their money but they keep all of the prizes they have won so far.

8. The game continues until the entire phrase is revealed (or one player guesses the complete phrase)
