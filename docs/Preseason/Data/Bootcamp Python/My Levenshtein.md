---
sidebar_label: 'My Levenshtein'
sidebar_position: 5
---

# My Levenshtein

In this quest, you will implement a function to calculate the Qwasar version of a Levenshtein number between two strings. The Qwasar version of the Levenshtein number represents how similar two strings are by comparing their characters and counting the differences.

## 🚀 Key Features

- **String Comparison**: Analyze differences between two strings to calculate the Levenshtein difference.
- **Iteration and Indexing**: Use loops to iterate through characters and compare corresponding positions in strings.
- **Input Validation**: Handle edge cases, such as strings of different lengths.

## 📝 Task Requirements

1. **Directory Structure**: Exercise must be in its own directory - `ex00`.
2. **Git Usage**: Every exercise must be committed and pushed to Git
3. **File Naming**: File must be located in `ex00` directory, a with following name `my_levenshtein.py`
4. **No Test Files**: Do not include any test files in your submissions
5. **Gandalf Testing**: All exercises must pass the gandalf test

## 🛠️ Useful resources for accomplishing this task

### String Comparison Basics
- [String Operations in Python](https://www.w3schools.com/python/python_strings_methods.asp)
- [Enumerate Function in Python](https://docs.python.org/3/library/functions.html#enumerate)
- [Understanding String Indexing](https://stackoverflow.com/questions/8848294/how-to-get-char-from-string-by-index)

### Tips
- **Check Input Lengths Early**: Before comparing strings, validate that their lengths are equal. If not, return `-1` immediately to save computation time.
- **Use `enumerate`**: The `enumerate` function is helpful when you need both the index and the character during iteration.
- **Count Differences**: Increment a counter each time characters at the same position in the two strings differ.

## 🧪 Test Cases

| Input Strings                 | Expected Output | Explanation                                                                 |
|-------------------------------|-----------------|-----------------------------------------------------------------------------|
| `"GGACTGA"`, `"GGACTGA"`      | `0`             | Both strings are identical; no differences.                                |
| `"ACCAGGG"`, `"ACTATGG"`      | `2`             | Differences at positions 2 and 4 (C vs. T and G vs. T).                    |
| `"GGACGGATTCTG"`, `"AGG"`     | `-1`            | Strings are of different lengths, so the result is `-1`.                   |
| `"AAB"`, `"ABB"`              | `1`             | Difference at position 1 (`A` vs. `B`).                                    |
| `"A"`, `"A"`                  | `0`             | Single-character strings are identical.                                    |
| `""`, `""`                    | `0`             | Both strings are empty, so no differences.                                 |
| `"QWERTY"`, `"qwerty"`        | `6`             | Every character differs due to case sensitivity (uppercase vs. lowercase).|
