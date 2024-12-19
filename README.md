# Tic Tac Toe with Reinforcement Learning

## Overview
This project implements a Tic Tac Toe game where reinforcement learning algorithms are used to automate player decisions. The implementation allows for both manual and automated gameplay using policies like Q-learning, SARSA, and Value Function.

## Installation Instructions

### Step 1: Install Python
Download and install Python 3.8.0 from [https://www.python.org/downloads/release/python-380/](https://www.python.org/downloads/release/python-380/).

During the installation, ensure the following features are selected:
- Add Python to PATH
- Install pip (Python package manager)
- Install IDLE (Integrated Development and Learning Environment)
- Install Tk/Tcl

### Step 2: Install Required Libraries
Open the command prompt (Windows key + R and type `cmd`) and run the following commands:

```bash
pip3 install numpy
pip3 install scipy
pip3 install pygame
```

### Step 3: Open Python IDLE
After installation, open Python IDLE by searching for “IDLE” in the Start menu.

### Step 4: Download the Source Code
Download the source file `tictactoe.py` and save it in a directory of your choice.

### Step 5: Run the Code
1. Open Python IDLE.
2. Go to `File` > `Open` and select the `tictactoe.py` file.
3. Run the script by selecting `Run` > `Run Module` or pressing `F5`.

---

## Tasks

### Task 1: Automating the Opponent’s Move
**Objective:** Automate the opponent (player 'O') moves using a probability transition function.

#### Changes Made:
1. **Board Layout Configuration:**
   - A variable is introduced to decide the board layout. For example, a value of `3` implies a 3x3 board, while `4` implies a 4x4 board.
2. **State and Action Space Modeling:**
   - The state space is defined as the set of all possible configurations of the board.
   - The action space consists of all valid moves for the opponent.
3. **Probability Transition Function:**
   - An arbitrary probability transition function is implemented to automate the opponent’s move.
   - The function uses the current state to decide the next move probabilistically.
4. **Manual Player Moves:**
   - The player (user) makes their moves manually using the mouse.

---

### Task 2: Automating Both Player Moves
**Objective:** Automate both the player (your move) and the opponent (player 'O') using defined policies.

#### Changes Made:
1. **Policy Implementation:**
   - Created arbitrary policies to dictate both players’ moves.
   - Policies include decision-making rules based on board state.
2. **Automated Gameplay:**
   - Mouse interaction is removed.
   - Both players’ moves are automated based on their respective policies.

---

## Reinforcement Learning Algorithms Implemented

1. **Q-Learning:**
   - A model-free reinforcement learning algorithm that uses a Q-value table to learn optimal actions based on rewards.
   - Applied to automate player moves.

2. **SARSA:**
   - A reinforcement learning algorithm that updates the Q-value based on the state-action-reward-next state-action sequence.
   - Ensures policies are followed during training.

3. **Value Function:**
   - Uses a value iteration approach to determine the best actions based on state values.
   - Applied to refine the opponent’s move automation.

---

## Output
The gameplay demonstrates multiple realizations of the game with different policies in action. The `TicTacToeVideo2.mp4` file showcases examples of the automated gameplay using the implemented policies.

---

## How to Run the Project
1. Follow the installation instructions.
2. Open and run `tictactoe.py` in Python IDLE.
3. Observe automated gameplay for both players based on the implemented policies.

---

## Contact
For questions or feedback, feel free to reach out!
