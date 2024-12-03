---
sidebar_label: '(exercise) my_iterative_factorial'
sidebar_position: 7
---

# my_iterative_factorial

In this exercise, you will implement a function to calculate the factorial of a given number using an iterative approach. The factorial of a number is the product of all positive integers less than or equal to that number. If an invalid input is provided, the function will return `0`.

## 🚀 Key Features

- **Iterative Approach**: Use loops to compute the factorial of a number.
- **Input Validation**: Handle invalid inputs, such as negative numbers.
- **Mathematical Computation**: Understand and implement the factorial operation.

## 📝 Task Requirements

1. **Gandalf Testing**: All exercises must pass the gandalf test

---

## 🛠️ Useful resources for accomplishing this task

### Factorial Basics
- [Understanding Factorial](https://www.mathsisfun.com/numbers/factorial.html)
- Factorial is denoted by `n!` and is calculated as `n * (n - 1) * (n - 2) * ... * 1`.
  - Example: `4! = 4 * 3 * 2 * 1 = 24`

### C Programming Loops
- [For Loop in C](https://www.tutorialspoint.com/cprogramming/c_for_loop.htm)
- [While Loop in C](https://www.geeksforgeeks.org/loops-in-c/)

---

## 🧪 Test Cases

| Input   | Expected Output | Explanation                                     |
|---------|-----------------|-------------------------------------------------|
| `2`     | `2`             | `2! = 2 * 1 = 2`.                              |
| `3`     | `6`             | `3! = 3 * 2 * 1 = 6`.                          |
| `4`     | `24`            | `4! = 4 * 3 * 2 * 1 = 24`.                     |
| `0`     | `1`             | By definition, `0! = 1`.                       |
| `-1`    | `0`             | Factorial is undefined for negative numbers.   |

---

## 💡 Tips for Beginners
1. **Start with Base Cases**: Factorial of `0` is `1` by definition. Factorials of negative numbers should return `0`.
2. **Use an Iterative Approach**: Loops (`for`, `while`) are well-suited for computing factorials.
3. **Debugging Tip**: Print intermediate results during iterations if your output is incorrect.