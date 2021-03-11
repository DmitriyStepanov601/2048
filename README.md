# 2048

This application is an interpretation of the famous game 2048, the essence of which is to get a tile of the nominal value "2048" (if desired, you can continue further).

Rules of the game:
1) In each round, a tile of the nominal value "2" (with a probability of 90 %) or "4" (with a probability of 10%) appears.
 
2) By pressing the arrow, the player can throw all the tiles of the playing field to one of the 4 sides. If two tiles of the same denomination "collide" with each other when dropping, they turn into one, the value of which is equal to the sum of the connected tiles. After each turn, a new tile with a face value of "2" or "4"appears on the free section of the field. If the location of the tiles or their face value does not change when the button is clicked, the move is not made.

3) If in one row or in one column there are more than two tiles of the same denomination, then when they are dropped, they begin to connect from the side to which they were directed. For example, the tiles in the same row (4, 4, 4) will turn into (8, 4) after a move to the left, and (4, 8) after a move to the right. This processing of ambiguity allows you to more accurately form the strategy of the game.

4) For each connection, the game points are increased by the face value of the resulting tile.

5) The game ends in defeat if it is impossible to perform an action after the next move.

After the game ends, a message is displayed that the game is over. To start the game again, press the ESC key.

![2048](https://user-images.githubusercontent.com/61186198/110749691-837f0180-8252-11eb-8946-9d99a53e2c52.gif)
