````
# ✊✋✌️ Rock–Paper–Scissors (Java CLI Game)

A simple **Rock–Paper–Scissors game** written in **Java**.  
This runs in the command line and lets a user play **3 rounds** against the computer.  

The computer's moves are randomized, and results are printed after each round.  
This project was made as a Java practice exercise (using `Scanner` for input and `Random` for computer choices).

---

## 🎮 Gameplay Instructions

- The game plays **3 rounds**.  
- On each round:
  1. The player is asked for input:
     - `0` → Rock  
     - `1` → Scissors  
     - `2` → Paper  
  2. The computer randomly generates its move.  
  3. The result is displayed:
     - Player wins  
     - Computer wins  
     - Tie  

- If you input anything greater than `2`, the game stops with an error message.

---

## 🖥️ Example Run

```bash
This is a rock,paper,scissor game,Given below are methods to play this game:
Enter (0) for rock,(1) for scissor and (2) for paper

Round-1
Enter your choice, to play:
0
Players move: 0
Computer's move: 2
ComputerA2 wins
PlayerA1 loses

Round-2
1
Player's move: 1
Computer's move: 2
PlayerA3 wins
ComputerA4 loses

Round-3
2
Player's move: 2
Computer's move: 2
It's a Tie match!
````

---

## 📂 Files

* `JavaExercise02.java` → Main source file (3 rounds of gameplay)
* `README.md` → This file

---

## ⚙️ How to Compile and Run

Make sure you have **Java installed** (JDK 17+ recommended).

1. Compile:

   ```bash
   javac JavaExercise02.java
   ```

2. Run:

   ```bash
   java JavaExercise02
   ```

---

## 💡 Features

* ✅ CLI-based
* ✅ Randomized computer moves
* ✅ 3 rounds gameplay
* ✅ Handles invalid input (basic error message)

---


## 🚀 Future Improvements

* [ ] Add a scoreboard to track wins/losses/draws across rounds.
* [ ] Ask player how many rounds to play.
* [ ] Clean up repeated code with a **method for a single round**.
* [ ] Fix random range so paper is always included.
* [ ] Add replay option after 3 rounds.

---

