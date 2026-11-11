# QuizWiz – Interactive Flashcard & Quiz Management Application

QuizWiz is a client-side study application built with React, Tailwind CSS, and browser localStorage. It lets students organize study decks, review flashcards, take practice quizzes, and monitor quiz results.

## Features implemented

1. **Deck management** – create, edit, view, and delete study decks.
2. **Flashcard management** – add, edit, and delete questions and answers.
3. **Interactive flashcard mode** – flip cards, move to the previous or next card, and see study progress.
4. **Practice quiz** – answer multiple-choice questions, receive immediate feedback, and view the final score.
5. **Search and category filter** – find decks by title or subject.
6. **Deck randomizer** – shuffle the card order before a study session or quiz.
7. **Performance dashboard** – review past quiz scores and average performance.
8. **Local persistence** – decks and quiz history are saved in the browser using localStorage.

## Requirements

- Node.js (LTS recommended)
- npm
- Visual Studio Code (recommended)

## Run the project

1. Extract the ZIP file.
2. Open the `quizwiz-prototype` folder in Visual Studio Code.
3. Open the VS Code terminal (**Terminal → New Terminal**).
4. Install the project dependencies:

   ```bash
   npm install
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Build for production

```bash
npm run build
```

## How data is saved

QuizWiz saves decks and quiz history in the current browser's `localStorage` under the key `quizwiz-data-v1`. Data stays in that browser on that device. Clearing browser storage or using another browser/device may remove or not show the saved data.

## Suggested live demonstration

1. Open the Dashboard and point out the deck, flashcard, and average-score summaries.
2. Open **My Decks** and search for a subject.
3. Create a new deck, then add two or more flashcards.
4. Edit one flashcard and delete another (use a sample card).
5. Open the deck and demonstrate **Study Cards**, including flip, Previous, and Next.
6. Demonstrate **Shuffle & Study**.
7. Start a quiz, select answers, and show the instant feedback and final score.
8. Open **Study Progress** and show the saved quiz history.

## Notes

- The app is a prototype and has no login, backend database, or cloud synchronization.
- Quiz answer choices are generated from answers already present in the selected deck. For useful multiple-choice quizzes, create at least two flashcards with different answers.
- This project uses Tailwind CSS utilities and additional custom CSS for the visual design.
