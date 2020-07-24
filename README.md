#Marscolonization

In general in game.js all what we need to do, is:
1. A 1D Array called "gameData" to store the players moves.
2. Draw the board on the canvas.
3. add Event listener to the CANVAS.
4. Determine which SPACE on THE BOARD the player has clicked on.
5. Update the gameData array. (if the space clicked by the player is empty)
6. Draw the player's move on the board (canvas).
7. check if this player wins. if wins we show the game over message. and stop the game.
8. If it doesn't win, we check for a tie game, if it's a tie we show the game over message. and stop the game.
9. If there is no winner and it's not a tie game, we give the turn to other player.

