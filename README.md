# WordGame

## How to Play

This is a simple word game all about making ends meet! At the start of the
game, players can choose a category. From this category, players must take
turns thinking of words related to the chosen category. The catch is that
each word must begin with the same letter the previous word ended with.

For example, say the category is Countries, and Player 1 chooses the first
word as "Canada". Player 2 must then choose a country that starts with "A",
the last letter of "Canada". If Player 2 chooses "Afghanistan", then Player
3 must start their country of choice with the letter "N", and so on.

No duplicate words allowed, and each player has a set time limit to think
of their word. This time limit can be changed in the settings. Each correct
word gives 1 point to the player. If a player can't think of a word or runs
out of time, the first player to give a correct answer gets to steal a point.
The game ends when no players can think of a word, or the round limit is hit.

## Technical 

Technologies used:

- Socket.io (client/server side)
- Express (server creation)
- React (client side)
- NodeJS
- HTML