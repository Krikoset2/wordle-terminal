# 🕵️‍♂️ Wordle Terminal & Cracker

This repo contains two Python scripts related to Wordle-like puzzles:

1. **`wordle_terminal.py`**: A terminal-based Wordle game where you guess a 5-letter word. 🎮
2. **`wordle_cracker.py`**: A script to crack a Wordle-like puzzle using feedback. 🔍

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- `colorama` library

Install the required library with:
```sh
pip install colorama
```

### `wordle_terminal.py` 🎮

Play a 5-letter Wordle game in the terminal.

**Run the script:**
```sh
python wordle_terminal.py
```

**Features:**
- Guess a 5-letter word in up to 6 tries.
- Colored feedback for guesses.

### `wordle_cracker.py` 🔍

Automatically cracks a Wordle-like puzzle based on feedback.

**Run the script:**
```sh
python wordle_cracker.py
```

**How to Use:**
- Provide feedback as `1` (correct position), `2` (wrong position), `3` (incorrect letter).
