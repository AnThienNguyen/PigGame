# Pig Game
A two player dice game programmed in JavaScript. Each player alternated turns rolling the die. The player who rolls the die will accumulate points based on the numbers they have rolled. Each time a player rolls their die, they have the option to either hold their current value or pass their turn to the next player. The players get to roll as many times as they want as long as they do not roll a 1. If a 1 is rolled, their round score is lost and the turn will be passed to the next player. First person to reach 100 wins the game. 
This project was created to learn JavaScript DOM manipulation. With the HTML DOM, JavaScript can create dynamic HTML by changing, removing, and adding elements and attibutes.

## GAME RULES:
* The game has 2 players, playing in rounds
* In each turn, a player rolls a dice as many times as he whishes. Each result get added to his ROUND score
* BUT, if the player rolls a 1, all his ROUND score gets lost. After that, it's the next player's turn
* The player can choose to 'Hold', which means that his ROUND score gets added to his GLBAL score. After that, it's the next player's turn
* The first player to reach 100 points on GLOBAL score wins the game

## CODING CHALLENGES
Change the game to follow these rules:
* A player loses his ENTIRE score when he rolls two 6 in a row. After that, it’s the next player’s turn
* Add an input field to the HTML where players can set the winning score, so that they can change the predefined score of 100
* Add another dice to the game, so that there are two dices now. The player loses his current score when one of them is a 1

### Built With
* HTML
* CSS
* JavaScript