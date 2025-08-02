# US-States-Game
This interactive game challenges users to correctly name all 50 U.S. states. Built using the Python turtle graphics module and pandas for data handling, the game displays a blank map of the United States and prompts the player to guess state names. For each correct guess, the state name is written on the map at the appropriate coordinates.
# 🗺️ U.S. States Guessing Game

An interactive geography quiz game built using Python's turtle graphics module and pandas. The game helps users learn the names and locations of all 50 U.S. states.

## 🎮 How It Works

- A blank map of the United States is displayed using a turtle graphics window.
- The user is prompted to enter the name of a U.S. state.
- If the guess is correct, the state's name appears at its location on the map.
- The game continues until all 50 states are guessed or the user types "Exit".
- Upon exiting early, a `states_to_learn.csv` file is generated listing the states not yet guessed.

## 🧰 Technologies Used

- **Python**
- **turtle** — For interactive map and graphics.
- **pandas** — For handling CSV data (state names and coordinates).

## 📁 Files

- `MAIN.ipynb` — Main game logic and interface.
- `50_states.csv` — Contains names and x-y coordinates of each state.
- `blank_states_img.gif` — Background image of the U.S. map.
- `states_to_learn.csv` — List of missed states (generated if user exits early).

## 🚀 How to Run

1. Ensure all files (`MAIN.ipynb`, `50_states.csv`, `blank_states_img.gif`) are in the correct directory.
2. Run the notebook in Jupyter or execute the Python script.
3. Enjoy learning U.S. states!

## 📌 Educational Goal

Improve your U.S. geography knowledge in a fun, interactive way!

---
Created with ❤️ using Python.
