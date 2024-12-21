The code you provided is for a quiz app with a clean, interactive design. Here's a detailed description of its functionality:

Purpose:

This is a simple, timed quiz application that allows users to answer multiple-choice IT-related questions. It provides immediate feedback for each answer, tracks the user's score, and shows a detailed result at the end of the quiz.

Key Features:

1. Start Screen:

Displays a welcome message and a "Start Quiz" button.

Once clicked, the quiz screen appears with the first question.



2. Quiz Screen:

Each question is displayed with multiple-choice options.

A timer starts at 30 seconds, counting down until the user has to answer.

The user selects an answer by clicking on one of the options, and the app checks whether it is correct or incorrect.

The "Next" button is initially disabled and becomes enabled only after selecting an answer.



3. Timer:

A countdown timer of 30 seconds for each question.

If the timer reaches zero, the user can no longer select an answer, and the "Next" button is enabled to move to the next question.



4. Answer Feedback:

When an answer is selected, it’s immediately highlighted in green (for correct) or red (for incorrect).

After answering, the choices are disabled to prevent further changes.



5. Result Screen:

Once the quiz is completed, the user's score (correct/incorrect answers) is shown.

A list of correct answers for each question is displayed for review.



6. Restart Option:

A "Restart" button allows the user to start the quiz again from the beginning, resetting all data (score, correct/incorrect answers, timer).




Quiz Data:

The quiz contains 10 multiple-choice questions, all related to basic IT concepts like HTML, CPU, RAM, programming languages, and computer history. Each question has four options, and only one of them is correct.

Flow of the Quiz:

1. Start the Quiz:

The user clicks the "Start Quiz" button on the start screen.



2. Answer Questions:

The app displays each question with multiple choices. The user selects an answer.

The app checks if the answer is correct, updates the score, and highlights the choice in green or red.

The user then clicks "Next" to proceed to the next question.



3. Time Limit:

If the timer reaches zero, the app disables further interactions for that question and allows the user to move to the next question.



4. Completion:

Once all questions are answered, the result screen shows the score, the number of correct and incorrect answers, and a list of correct answers.



5. Restart:

The user can restart the quiz at any time by clicking the "Restart" button on the result screen.




How It Works:

1. Shuffling Choices:

The choices for each question are randomly shuffled to ensure the order is different each time the quiz is taken.



2. Timer Control:

A countdown timer runs for 30 seconds per question. When the time is up, it automatically moves to the next question.



3. Answer Evaluation:

The app compares the selected answer with the correct answer and updates the score accordingly.



4. Result Display:

After the quiz ends, the score, number of correct/incorrect answers, and a list of correct answers for each question are shown.




CSS:

The page uses a gradient background with soft blue and pink hues.

The quiz container has a clean design with rounded corners, a subtle shadow, and central alignment.

Buttons and list items have hover effects for interactivity.


JavaScript:

shuffleArray: Randomizes the order of answer choices.

loadQuestion: Displays the current question and its shuffled choices.

checkAnswer: Validates the user's answer, updates the score, and changes the color of the selected option.

startTimer: Starts and updates the countdown timer for each question.

showResult: Displays the final score and the correct answers list after all questions are completed.


This app can be extended with more questions, added difficulty levels, or further customizations to improve user experience.

