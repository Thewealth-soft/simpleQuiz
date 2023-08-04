# Simple Quiz-App

This is a simple quiz application built using HTML, CSS, and JavaScript.

## Features

- Presents questions and multiple-choice answers.
- Calculates and displays the user's score.
- Provides instant feedback on correct and incorrect answers.
- Allows the user to proceed to the next question.

## Usage

1. Clone this repository to your local machine.

```bash
git clone https://github.com/your-username/quiz-app.git
```

2. Open the index.html file in a web browser.

3. Answer the questions and see the feedback.

## How It Works

The list_questions array contains an array of question objects, each with a question, answer options, and the correct answer index.

The quiizer function populates the question and answer options on the page based on the current question index.

The check_correct function handles user's answer selection, updates the score, and provides feedback.

The nextBtn event listener increments the counter, resets the answer selection, and updates the UI for the next question.

Contributing
Feel free to contribute by opening issues or pull requests.

