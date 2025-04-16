# Missionaries_Cannibals_Game
# 3 Missionaries and 3 Cannibals River Crossing Game

This project recreates the classic **3 Missionaries and 3 Cannibals River Crossing Puzzle** using Python. The goal is to transfer all the missionaries and cannibals from one side of the river to the other without breaking the rules.

## Game Objective
The objective of the game is to safely transfer all the missionaries and cannibals from the right side to the left side of the river using a boat, while avoiding any scenario where the number of cannibals outnumbers the missionaries on either side.

You win when:
- All the missionaries and cannibals are successfully transferred to the left side.

You lose if:
- Cannibals outnumber missionaries on either side of the river.

## Game Rules
1. Only 1 or 2 people are permitted on the boat to travel at a time.
2. The number of passengers (missionaries or cannibals) on the boat cannot exceed the number of available missionaries or cannibals on either side of the river.
3. **You lose** if at any point the number of cannibals exceeds the number of missionaries on either side.
4. **You win** if you successfully transfer all the missionaries and cannibals to the left side of the river.

## Notebook Structure
The notebook is divided into the following lessons:
- **Lesson 1:** Setting up the initial environment of the game.
- **Lesson 2:** Adding valid and invalid conditions along with the corresponding operations.
- **Lesson 3:** Combining all segments of the code to build the complete game logic.
- **Lesson 4:** Enhancing the game with emoticons to improve the user interface.

## Sample Code
Here is a sample initialization code snippet from the project:
```python
boat_side = 'Right'
missionaries_on_right = 3
cannibals_on_right = 3
missionaries_on_left = 0
cannibals_on_left = 0

print("ML=", missionaries_on_left, "CL=", cannibals_on_left, "| -----B |", "MR=", missionaries_on_right, "CR=", cannibals_on_right)
```

## How to Run the Project
Clone this repository:
git clone https://github.com/Vaishnavi-76304/Missionaries_Cannibals_Game.git

Open the Jupyter Notebook:
jupyter notebook Missionary_Cannibals.ipynb

Follow the steps in the notebook to run the solution and understand the logic.

