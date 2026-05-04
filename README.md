# MathBrain-Generator 🧠🔢

![C++](https://img.shields.io/badge/Language-C++-orange.svg)
![Type](https://img.shields.io/badge/Project-Educational-blue.svg)
![Status](https://img.shields.io/badge/Build-Stable-green.svg)

An advanced command-line mathematical quiz system built with C++. This engine generates intelligent, randomized arithmetic challenges based on user preferences, offering a structured way to practice mental math across various difficulty levels.

## 🚀 Core Features
*   **Difficulty Scaling:** Four distinct levels including `Easy`, `Medium`, `Hard`, and a `Mixed` mode for unpredictable challenges.
*   **Operation Versatility:** Supports Addition, Subtraction, Multiplication, Division, and a `Random Mix` of all four.
*   **Intelligent Logic:** Automatically generates operands based on the selected difficulty range (e.g., Easy: 1-10, Hard: 50-100).
*   **Real-time Feedback:** Instant grading of each answer with visual "Pass/Fail" final results.
*   **Data Encapsulation:** Uses structured data (`structs`) to manage complex quiz states and question lists.

## 🛠️ Technical Implementation
This project serves as a demonstration of robust C++ programming techniques:
*   **Enums & Structs:** Used for managing difficulty levels, operation types, and comprehensive quiz data.
*   **Pass by Reference:** Efficiently updates quiz results using reference parameters (`stQuizz &Quizz`).
*   **Randomization Engine:** Leverages `<ctime>` and `<cstdlib>` for high-entropy question generation.
*   **Error Prevention:** Includes logic to handle division by zero and input validation.

## 🎮 How to Use

1.  **Initialize:** Upon startup, specify the number of questions you want to tackle.
2.  **Configure:** Choose your difficulty level (1 to 4) and the arithmetic operation type (1 to 5).
3.  **Solve:** The engine will present questions one by one. Enter your answer and press `Enter`.
4.  **Review:** After the final question, the system will display your total score and whether you passed the challenge.
5.  **Repeat:** You can instantly restart a new session with different configurations.

## 📦 Requirements
*   A standard C++ compiler (GCC/G++, Clang, or MSVC).
*   Console/Terminal environment.


Distributed under the MIT License. See LICENSE for more information.

Created by [Abdulrahman Faisal] - Feel free to connect!

## 🔧 Installation
```bash
# Clone the repository
git clone [https://github.com/YourUsername/MathBrain-Generator.git](https://github.com/YourUsername/MathBrain-Generator.git)

# Compile the project
g++ -o MathQuiz main.cpp

# Run the application
./MathQuiz
