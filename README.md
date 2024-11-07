
# Quizzler: A Python Quiz Application

Quizzler is a Python-based quiz application that presents users with a series of true/false questions from the Open Trivia Database API. The app is built with a simple graphical user interface (GUI) using `tkinter`, and it keeps track of the user's score throughout the quiz.

## Features

- Fetches 10 random true/false questions from the Open Trivia Database API.
- Displays questions in a user-friendly GUI.
- Provides instant feedback on user responses.
- Tracks and displays the user's score.
- Ends the quiz when all questions are answered.

## Project Structure

- `data.py`: Handles the API call to fetch quiz questions from the Open Trivia Database.
- `main.py`: Main script to run the application, initializing the question bank and launching the GUI.
- `question_model.py`: Defines the `Question` class, representing each question with its text and answer.
- `quiz_brain.py`: Contains the `QuizBrain` class, managing quiz logic, question navigation, and answer validation.
- `ui.py`: Implements the `QuizInterface` class, creating the GUI with tkinter and handling user interactions.
