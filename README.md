

## 🎮 Binary Number Guessing Game

This is a console-based number guessing game where the player attempts to guess a randomly generated **decimal number** by providing their guesses in **binary format**. The game provides hints (higher/lower) after each incorrect guess.

-----

## ✨ Features

  * **Random Number Generation:** A secret decimal number is randomly selected within a defined range.
  * **Binary Input:** The player inputs their guesses as a **string of '0's and '1's**.
  * **Input Validation:** The game checks if the input is a valid binary string and if its decimal equivalent falls within the game's allowed range.
  * **Hints:** After each incorrect guess, the player receives feedback indicating if the correct number is **higher** or **lower** than their guess.
  * **OOP Design:** The game structure is implemented using **Object-Oriented Programming** principles (e.g., classes for the Game, Player, etc.).
  * **DSA Integration:** Key functionalities, like **binary to decimal conversion** or managing high scores, utilize **Data Structures and Algorithms** concepts.

-----

## 🛠️ Technologies & Concepts Used

### 💻 Development Environment

  * **Language:** C++
  * **Platform:** Terminal/Console Application

### 🧠 Core Concepts

The project was designed to demonstrate and apply key programming concepts:

  * **Object-Oriented Programming (OOP):**
      * **Classes and Objects:** Used to model game entities (e.g., `Game`, `Player`).
      * **Encapsulation:** Protecting game state variables and logic.
      * **Abstraction:** Providing simple interfaces to complex logic (like running the game).
  * **Data Structures and Algorithms (DSA):**
      * **Binary Representation:** The fundamental game mechanic involves converting binary input to its decimal equivalent.

[Image of Binary to Decimal Conversion Process]

```
* **Input Handling/Validation:** Algorithms for efficient string manipulation and validation of binary input.
```

-----

## 🚀 How to Run the Game

### Prerequisites

You need a C++ compiler (like g++ or clang) installed on your system.

### 1\. Compilation

Navigate to the root directory of the project in your terminal and compile the source code (assuming your main file is `main.cpp`):

```bash
g++ main.cpp -o binary_guess
```

*(Adjust the file name as necessary if you have multiple source files, e.g., `g++ *.cpp -o binary_guess`)*

### 2\. Execution

Run the compiled executable from your terminal:

```bash
./binary_guess
```

### 3\. Gameplay

Follow the on-screen prompts. When asked for a guess, enter the number in binary form (e.g., enter **`1010`** to guess the number **10**).

-----

## 💡 Learning & Improvement

This project served as a practical exercise in applying both OOP and foundational DSA concepts in a single, working application.

Would you like me to add a specific section for **High Scores** or detail the **Binary to Decimal Conversion Logic**?
