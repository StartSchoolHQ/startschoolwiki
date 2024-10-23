---
sidebar_label: 'My Mastermind'
sidebar_position: 3
description: A complete guide to the Game Guessing Program - a fun and challenging game where players guess a series of unique numbers from 0 to 8.
---

# My_mastermind

Welcome to the **Game Guessing Program**, where players guess a series of unique numbers from `0` to `8`. Below are the key rules and features of the game.

## 🚀 Key Features

- **Supports Flags**: Use `-c` and `-t` flags in any order and simultaneously.
- **Unique Digits**: Each guess consists of digits from `0` to `8`, with no duplicates.
- **Input Validation**: Invalid guesses (non-digits, wrong length, duplicates) don't advance the round.
- **Graceful Exit**: Exit cleanly anytime with `Ctrl + D`.

## 📝 Game Rules

1. **Digits**: The game uses only digits from `0 to 8` (no duplicates).
2. **Valid Length**: Guesses must match the required length.
3. **Invalid Inputs**: Non-digit, wrong length, or duplicate digits trigger an error but don't advance the round.

## ⚙️ How the Program Works

- **Flags**:
  - `-c`: Configuration mode
  - `-t`: Testing mode
- **Exit**: `Ctrl + D` for graceful exit without crashing.
- **Correct Guess Display**: For testing, the correct answer is shown at the end.

## ⚠️ Error Handling

- Non-digit input
- Wrong length (too long/short)
- Duplicate digits

These will trigger an error without advancing the round.

## 🛠️ Example Usage

Run the game with flags:

```bash
./game -c -t
