# 🎯 Hangman Game – Modular Python Implementation

## 📌 Project Overview

This project is a **command-line implementation of the classic Hangman game**, developed using **Python** with a modular structure.

The game randomly selects a word from a predefined word list and allows the user to guess letters within a limited number of lives. Visual hangman stages update dynamically based on incorrect guesses.

The focus of this project is on:

* Structured program design
* Modular file organization
* Game loop control
* State tracking and logic flow

---

## 🎯 Why This Project?

This project was built to practice:

* Writing structured Python programs across multiple files
* Separating logic, data, and presentation
* Managing game state (lives, guesses, win/lose conditions)
* Implementing real-world rule-based systems

Unlike smaller beginner programs, this project demonstrates:

* File imports
* Reusable modules
* Controlled game loops
* State persistence across iterations

These are important stepping stones toward larger software systems and AI-based applications.

---

## 🧠 Core Concepts Used

* Python modules and imports
* Random selection using `random.choice()`
* Loops (`while`)
* Conditional statements
* List handling
* String manipulation
* State tracking using variables
* Game flow control
* ASCII art rendering

---

## 🗂️ Project Structure

```
hangman-game-python/
│
├── main.py
├── hangman_words.py
├── hangman_art.py
└── README.md
```

### 🔹 `main.py`

Contains:

* Core game logic
* Game loop
* Life tracking
* Win/Loss detection
* Display updates 

### 🔹 `hangman_words.py`

Contains:

* Large predefined word list for random selection 

### 🔹 `hangman_art.py`

Contains:

* ASCII art logo
* Hangman stages displayed as lives decrease 

This separation improves readability and maintainability.

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/hangman-game-python.git
   ```

2. Navigate to the directory:

   ```bash
   cd hangman-game-python
   ```

3. Run the game:

   ```bash
   python main.py
   ```

No external libraries are required.

---

## 🎮 How the Game Works

1. A word is randomly selected.
2. The user guesses one letter at a time.
3. If the guess is correct:

   * The letter is revealed.
4. If incorrect:

   * A life is deducted.
   * The hangman stage updates visually.
5. The game ends when:

   * The word is fully guessed (Win)
   * Lives reach zero (Lose)

---

## 🎓 Learning Outcomes

Through this project, I strengthened my ability to:

* Design modular Python programs
* Manage game state efficiently
* Separate concerns across files
* Implement loop-based interactive systems
* Translate real-world rules into executable logic

---

## 🚀 Future Improvements

* Add difficulty levels
* Track guessed letters to prevent repetition
* Add replay functionality
* Improve input validation
* Convert into a GUI version
* Implement scoring system

---

## 👤 Author

**A.B.N.S Rishik**
First-Year B.Tech (Artificial Intelligence) Student
SRM Institute of Science and Technology, Ramapuram Campus

📍 Chennai, India
✉️ Email: [rishikcr72401@gmail.com](mailto:rishikcr72401@gmail.com)
🔗 LinkedIn: [https://www.linkedin.com/in/abnsrishik](https://www.linkedin.com/in/abnsrishik)

---

⭐ *Building structured, modular Python systems as a foundation for advanced AI development.*

---

