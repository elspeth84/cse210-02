# cse210-02
Programming with classes - Week 02 group project
Hilo is played according to the following rules.

The player starts the game with 300 points.
Individual cards are represented as a number from 1 to 13.
The current card is displayed.
The player guesses if the next one will be higher or lower.
The the next card is displayed.
The player earns 100 points if they guessed correctly.
The player loses 75 points if they guessed incorrectly.
If a player reaches 0 points the game is over.
If a player has more than 0 points they decide if they want to keep playing.
If a player decides not to play again the game is over.

Identify the objects in your program. Look for the central nouns in the game requirements. Narrow down your list to just the most essential ones. For each object, ask yourself, "is this an object, or the state in another object?"

Define the responsibility, behaviors and state for each object. Look for related verbs in the game requirements to help you. When you are working on an object's state, ask yourself, "what information is required to fulfill its behaviors?"

Identify the relationships between your objects. Look at the user interface in the game requirements to help you. Try roll playing the objects as you talk through a typical game, asking other objects to perform specific behaviors, etc.

Translate your object designs to class designs. This is not a coding task. It is simply deciding what the class name as well as method names, parameters and return types will be. It is also deciding what attribute names and data types will be.

Document your objects and classes so that everyone can refer to them throughout the project. The graphical notation that follows is often the easiest way. It really doesn't matter how you do it though. It just matters that you do.

...

import random

main function
#Call number genorator ("The card is: {number genorator})
#ask user input if card is higher or lower? [h/l]
print(Next card was: {number gentorator})
print(Your score is: {call point calculator})
#ask user -(" Play again? [y/n] ")
#if/

function number genorator (13)
#generate a number 1-13 randomly

return 1 random number (card)

function point calculator()
declare empty list that holds points = []
if user chooses a certain number 
points += 100
else points -= 75

return total user points

What we will study this week: How to generate classes and how to incorporate those in our program

