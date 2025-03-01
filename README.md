# React Quiz App

This is a simple quiz application built with React, created as part of a course on Udemy. The app allows users to answer questions and displays a summary of their performance at the end. It features a timer for each question, tracks user answers, and provides a breakdown of correct, incorrect, and skipped answers.

## Features:
- **Multiple-choice questions**: Users answer questions with one correct option.
- **Question timer**: Each question has a timer, and the user must answer before time runs out.
- **Performance summary**: After the quiz, users get a summary of their performance with a percentage of correct, incorrect, and skipped answers.
- **Easy to use**: A clean and straightforward UI where users can quickly answer questions and see their results.

## Technologies Used:
- **React** (Hooks: `useState`, `useCallback`, `useRef`)
- **JavaScript**
- **CSS** (for styling)
  
## How It Works:
- The app loads a list of questions from a `QUESTIONS` array.
- Each question has multiple answers, but only one correct answer.
- The user selects an answer, and the app moves to the next question or skips it.
- Once all questions are answered, a summary page is displayed showing how many questions were answered correctly, skipped, or answered incorrectly.

## How to Use:
1. Clone the repository:  
   `git clone https://github.com/klaudia-pruchnik/react-quiz-app.git`
   
2. Install dependencies:  
   `npm install`
   
3. Run the app:  
   `npm start`

4. Answer the questions and see your results!

## License:
This project is for educational purposes and created as part of a React course on Udemy.
