# Project-proposal
What the Project Does
This project is a Java-based quiz game where a player answers multiple-choice questions. After completing the quiz, the player’s score is saved in a MySQL database, and the top 5 scores (leaderboard) are shown.
---
How It Works
1. Player Name Input
When the program starts, it asks the player to enter their name.
2. Displaying Questions
The quiz window shows one question at a time with 4 options using radio buttons.
3. Answering Questions
The player selects an answer and clicks the Next button. If the answer is correct, the score increases.
4. Saving Score and Showing Leaderboard
After the last question:
The score is saved in the MySQL database.
The top 5 scores are shown using a popup message.
---
Main Parts of the Code
DatabaseManager: Connects to MySQL, saves scores, and retrieves the leaderboard.
Question: Holds a single question, its options, and the correct answer.
QuizGUI: The main GUI where the quiz runs.
QuizGame (Main): Starts the quiz by asking the name and launching the GUI.
--
Technologies Used
Java Swing for GUI
MySQL for storing scores
JDBC for database connectivity
