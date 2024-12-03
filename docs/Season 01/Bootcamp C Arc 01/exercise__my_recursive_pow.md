---
sidebar_label: '(exercise) my_recursive_pow'
sidebar_position: 9
---

# my_recursive_pow

In this exercise, you will implement a function to calculate the power of a number using recursion. The power operation calculates a number (`base`) raised to the exponent (`power`). An exponent less than `0` will return `0`, and no overflow handling is required.

## 🚀 Key Features

- **Recursive Approach**: Use function calls to calculate the power of a number.
- **Input Validation**: Handle edge cases, such as negative exponents.
- **Base Case and Recursion**: Define clear base cases to stop recursion.

## 📝 Task Requirements

1. **Gandalf Testing**: All exercises must pass the gandalf test

---

## 🛠️ Useful resources for accomplishing this task

### Power Function Basics
- [Understanding Power Operation](https://study.com/academy/lesson/how-to-find-the-power-of-a-number.html#:~:text=Lesson%20Summary-,The%20power%20of%20a%20number%20stands%20for%20how%20many%20multiples,by%20itself%20that%20many%20times.)
- Power calculates the result of multiplying a number (`base`) by itself `power` times:
  - Example: `2^3 = 2 * 2 * 2 = 8`.

### Recursion Basics
- [Recursion in C](https://www.geeksforgeeks.org/recursion/)
- Recursive functions are functions that call themselves with a reduced problem size.

---

## 🧪 Test Cases

| Base   | Exponent | Expected Output | Explanation                                     |
|--------|----------|-----------------|-------------------------------------------------|
| `2`    | `2`      | `4`             | `2^2 = 2 * 2 = 4`.                             |
| `2`    | `3`      | `8`             | `2^3 = 2 * 2 * 2 = 8`.                         |
| `2`    | `4`      | `16`            | `2^4 = 2 * 2 * 2 * 2 = 16`.                    |
| `5`    | `0`      | `1`             | Any number raised to the power of `0` is `1`.  |
| `3`    | `-1`     | `0`             | Negative exponents return `0` per task rules.  |
| `7`    | `1`      | `7`             | Any number raised to the power of `1` is itself. |

---

## 💡 Tips for Beginners
1. **Define Base Cases**: For powers, `base^0 = 1`. Handle negative exponents as invalid input by returning `0`.
2. **Recursive Formula**: For `base^power`, the recursive formula is `base * base^(power-1)`.
3. **Input Validation**: If the exponent is negative, return `0` immediately.
4. **Debugging Tip**: Print the intermediate results during recursion to understand the flow of execution.

---