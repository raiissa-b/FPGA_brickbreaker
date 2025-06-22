# FPGA_brickbreaker

The aim of this project was to make a game on a FPGA, we were given an incomplete prototype and had to add the missing modules as well as implement bonus features.
It contains the following modules:
- A clock divider : the Basys' clock frequency is 100 MHz but the game needed two clocks, one at 25 MHz and the other at 25 Hz.
- A VGA monitor that would give us Red, Green and Blue coded on 4 bits
- **Moving Colors** : this module generates a 12 bits colors that changes over time
- **Rotary** : an IP enabling us to move the platform using a rotary encoder
- **Game** : the module enabling the user to
  -    Choose the background color
  -    Choose which game to play (if two basys were available you could play a Pong game with someone else)
- **Mode** : the module that manages the game, whether it's paused, lost or won
- **Decor** : the module taking the current pixel and indicating whether it belongs to an object (wall, platform...), enables us to know when we hit an obstacle

  ![image](https://github.com/user-attachments/assets/4c911097-825d-43de-86e9-c7ec6b9a8632)
