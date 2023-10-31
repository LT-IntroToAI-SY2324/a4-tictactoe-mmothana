# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

    The most difficult part of the tic-tac-toe was the has_won code. I didn't know how to correctly include the right spots that counts as a win so my code was not correctly saying what was a win or not.

2. Explain how you would add a computer player to the game.

    I would add a computer player to the game by coding the O player to either choose a random spot that has not been chosen yet or the spot to best get the victory for the best.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

    I would make the computer player to play the best move every time by first making sure the other player is close to winning, if they have two in a row with the third open, then I would block the third spot. If the other player is not about to win, then I would place the O in the best available spot. The center spot is the best spot in tic-tac-toe with the corners being the second best so I would place the O in whichever tier is not taken yet.