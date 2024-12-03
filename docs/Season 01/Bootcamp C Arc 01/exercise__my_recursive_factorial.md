---
sidebar_label: '(exercise) my_recursive_factorial'
sidebar_position: 8
---

# my_recursive_factorial

In this exercise, you will implement a function to calculate the factorial of a given number using recursion. The factorial of a number is the product of all positive integers less than or equal to that number. Unlike the iterative approach, this solution leverages recursive function calls.

## 🚀 Key Features

- **Recursive Approach**: Use function calls to calculate factorial recursively.
- **Input Validation**: Handle invalid inputs, such as negative numbers.
- **Base Case and Recursion**: Define clear base cases to stop recursion.

## 📝 Task Requirements

1. **Gandalf Testing**: All exercises must pass the gandalf test

---

## 🛠️ Useful resources for accomplishing this task

### Recursion Basics
- [Recursion in C](https://www.geeksforgeeks.org/recursion/)
- Recursion is a method where a function calls itself with a reduced problem size.
  - Example: `n! = n * (n-1)!`.

### Factorial Basics
- [Understanding Factorial](https://www.mathsisfun.com/numbers/factorial.html)

---

## 🧪 Test Cases

| Input   | Expected Output | Explanation                                     |
|---------|-----------------|-------------------------------------------------|
| `2`     | `2`             | `2! = 2 * 1 = 2`.                              |
| `3`     | `6`             | `3! = 3 * 2 * 1 = 6`.                          |
| `4`     | `24`            | `4! = 4 * 3 * 2 * 1 = 24`.                     |
| `0`     | `1`             | By definition, `0! = 1`.                       |
| `-1`    | `0`             | Factorial is undefined for negative numbers.   |
| `5`     | `120`           | Computed recursively as `5 * 4 * 3 * 2 * 1`.   |

---

## 💡 Tips for Beginners
1. **Define Base Cases**: Recursion must stop at a base case. For factorials, this is `0! = 1` or `1! = 1`.
2. **Recursive Formula**: For `n!`, the recursive formula is `n * (n-1)!`.
3. **Input Validation**: If the input is negative, return `0` immediately since factorials of negative numbers are undefined.
4. **Stack Limitations**: Be aware that recursion uses the call stack. For very large inputs, this could cause a stack overflow.
5. **Debugging Tip**: Print intermediate recursive calls to understand the flow of execution.