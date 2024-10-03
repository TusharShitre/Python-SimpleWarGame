War Card Game Simulation
Welcome to the War Card Game Simulation project! This Python-based program simulates a card game known as "War" where two players compete against each other by drawing cards and comparing their values. The player with the higher card wins that round, and if both players draw cards of the same value, a "war" ensues. The game continues until one player runs out of cards.

Project Overview
This project is a simple Python simulation of the classic War card game, where:

Two players are dealt 26 cards each from a shuffled deck.
Players draw cards from the top of their decks and compare values.
The player with the higher-value card wins the round and collects both cards.
In case of a tie (when both cards have equal value), a "war" occurs, and additional cards are drawn.
The game ends when one player runs out of cards.
How the Game Works
Game Setup:

A standard deck of 52 cards is shuffled.
Each player (Player One and Player Two) is dealt half the deck (26 cards each).
Gameplay:

In each round, both players draw the top card from their decks and compare their values.
The player with the higher value wins the round and collects both cards.
If the values are the same, a "war" begins. Both players draw 5 additional cards, and the last card in the new set is compared to determine the winner. The winning player collects all the cards on the table.
End of the Game:

The game continues until one player runs out of cards. That player loses the game.
Project Structure
This project is built around three main classes:

Card: Represents a single playing card with a suit and rank.
Deck: Manages the creation, shuffling, and dealing of cards.
Player: Represents a player with their own deck of cards, along with methods to remove and add cards.
How to Run
Requirements:

This project runs entirely in Python and does not require any external libraries.
Python version 3.x is recommended.
Running the Game:

Copy the entire code into a Python environment or IDE (e.g., PyCharm, VS Code).
Run the script, and you’ll see the game being played in the console.
Each round will print the number of the current round and the outcome (whether one player wins or if there's a war).
Stopping the Game:

The game continues automatically until one player runs out of cards.
There’s no manual intervention required.
Rules
Winning a Round: The player with the higher-value card wins the round and collects both cards.
War: In the event of a tie, each player draws 5 more cards. If one player runs out of cards during a war, they automatically lose. Otherwise, the last card in the additional set is compared, and the winner collects all the cards.
End Condition: The game ends when one player has no cards left.
Future Enhancements
Some possible features to add in the future:

User Interface: Implementing a graphical interface for a more interactive experience.
Player Input: Allowing players to interact with the game (e.g., choosing when to draw cards).
Multi-Round Game: Adding the ability to play multiple games and keep track of overall wins and losses.
