
# Dot Drawing Canvas with Undo/Redo

This is a simple interactive web app that allows users to draw dots on a canvas by clicking, with **Undo** and **Redo** functionality implemented using two stacks.

## ✨ Features

- Draw dots by clicking anywhere on the canvas.
- Undo the last drawn dot.
- Redo an undone dot.
- Clear, minimal, and responsive UI.

## 🛠️ How It Works

- The app uses two stacks (`undoStack` and `redoStack`) to track the drawing history.
- Clicking the canvas adds a new dot to the `undoStack` and clears the `redoStack`.
- Clicking **Undo** pops the last dot from `undoStack` and pushes it to `redoStack`.
- Clicking **Redo** pops from `redoStack` and pushes back to `undoStack`.


