# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

The most difficult part was how to go about checking for a winner in the game_over and partially the has_won methods. Using my previous knowledge in java and with the minimal python I've learned, I thought I was meant to create a huge block of if statements! When I was shown the pythonic solution in class I felt ashamed because the solution was done in much fewer lines of code.

2. Explain how you would add a computer player to the game.

I would attempt to create a random function which the program would continuously call in a for loop, to choose a spot on the board until someone had won. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

It might be a good idea to give it some sort of learning algorithm. The more simulations that it runs, the more it learns the characteristics of the game. This way, it would eventually learn to choose the best moves after thousands or maybe tens of thousands of simulations. I am unaware of what these algorithms are called or the technical terms but that is what I think would be best.