# 🇺🇸 U.S. States Guessing Game

A fun Python game that helps you learn and practice the names of all 50 U.S. states!  
The player types in state names, and correct guesses are displayed on a blank U.S. map.

---

## Game Preview

![Game Output](screenshot-output.jpg)

---

## How the Game Works

- A blank U.S. map is displayed.
- The user is prompted to guess U.S. state names.
- When a correct state is guessed:
  - The state name appears on the map at the correct location.
  - The guess counter increases.
- The game continues until:
  - All 50 states are guessed, **or**
  - The user clicks “Cancel”.
- Any states not guessed are saved to a file called **`states_to_learn.csv`** for later practice.

---

## Technologies Used

- **Python**
- **turtle** (for graphics)
- **pandas** (for reading and writing CSV files)

---

## Files in This Project

- `main.py` – the main game script  
- `50_states.csv` – contains state names and x/y coordinates  
- `blank_states_img.gif` – background map image  
- `states_to_learn.csv` – generated after the game ends  
- `screenshot-ouput.png` – screenshot of the game output  

---

## ▶️ How to Run the Game

1. Make sure Python is installed on your computer.
2. Install pandas if you don’t already have it:
   ```bash
   pip install pandas
3. Ensure all files are in the same directory.

4. Run the program:
   ```bash
   python main.py

