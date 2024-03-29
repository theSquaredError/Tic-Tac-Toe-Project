# Programming Assignment: Reinforcement Learning Algorithms (CS533L)

Step 1: Install Python from https://www.python.org/downloads/release/python-380/

During installation please ensure that some features are selected (see that attached pic pythoninstallation.png)

Step 2: Now go to command prompt (Windows key + R and type 'cmd')

Run the following
```
pip3 install numpy

pip3 install scipy

pip3 install pygame
```

Step 3: After this open the python IDLE (see pic IDLE.png)

Step 4: Download the source code (tictactoe.py)

Step 5: From the IDLE go to File-->Open and open the file tictactoe.py

Step 6: Now Run-->Run Module


----------------------------------------------------

Task 1: 
---------
Declare a variable that decides the board layout (for example 3 implies 3 x 3 board, while 4 implies 4x4 board)
Make changes to the code such that the opponent (who plays 'O') is automated using a probability transition function.




Details
-------------------------
1) Model the state space and action space
2) Create an arbitrary probability transition function
3) Make use of the above probability transition function to decide the move of the opponent

In this part, your move will be performed by yourself using the mouse itself. Only the opponent move is automated


Task 2
-----------

1) Create an arbitrary policy
2) Make changes to the code to follow that policy (This means the mouse click is no more required. The code will follow the policy to find your move)


Please see the output video obtained (TicTacToeVideo.mp4). The video shows multiple realisations of the game when some policy is followed.
