# Tic-Tac-Toe

A two-player tic-tac-toe game built with React and Vite, following the official [React tutorial](https://react.dev/learn/tutorial-tic-tac-toe).

## Features

- Two players take turns placing **X** and **O** on a 3×3 board (X goes first).
- The status line shows whose turn it is, or the winner once three in a row is made.
- **Time travel:** every move is recorded in a history list, and you can jump back to any earlier move. Making a new move from a past position discards the moves that came after it.
- The current move is shown as text ("You are at move #…") instead of a button.
- Each move in the history shows where it was played as **(row, col)**.
- A toggle sorts the move history in ascending or descending order.
- The three winning squares are highlighted, and a message appears when the game ends in a draw.

## Play it

Live at **https://vale25611.github.io/Tic-Tac-Toe/** (deployed to GitHub Pages on every push to `main`).

## Run locally

```bash
npm install
npm run dev
```
