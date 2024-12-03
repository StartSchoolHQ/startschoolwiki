---
sidebar_label: '(exercise) my_print_alphabet'
sidebar_position: 6
---

# my_print_alphabet

In this exercise, you will create a function that displays the alphabet in lowercase on a single line, starting with the letter 'a' and ending with 'z'. Each character will be printed sequentially in ascending order, followed by a newline character.

## 🚀 Key Features

- **Character Iteration**: Use loops to iterate over characters from 'a' to 'z'.
- **Printing Characters**: Learn how to print characters in C using standard output functions.
- **Formatting**: Ensure proper output format with a newline character at the end.

## 📝 Task Requirements

1. **Gandalf Testing**: All exercises must pass the gandalf test

---

## 🛠️ Useful resources for accomplishing this task

### Printing Characters in C
- [putchar() function in C](https://www.geeksforgeeks.org/putchar-function-in-c/)
- [C Loops](https://www.tutorialspoint.com/cprogramming/c_loops.htm)

### ASCII Table
- ASCII values are numerical representations of characters. For example, `'a'` has an ASCII value of `97`, and `'z'` has a value of `122`. Use these values to iterate over the alphabet.
- [ASCII Table Reference](https://www.asciitable.com/)

---

## 🧪 Test Cases

| Input           | Expected Output               | Explanation                                |
|------------------|-------------------------------|--------------------------------------------|
| None            | `abcdefghijklmnopqrstuvwxyz\n`| Prints all lowercase letters followed by a newline. |

---

## 💡 Tips for Beginners
1. **Use ASCII Values**: You can iterate over characters just like numbers because they have corresponding ASCII values.
2. **putchar Function**: `putchar(c)` prints a single character to the standard output. It's simpler than `printf` for single characters.
3. **Newline Character**: Always remember to add a newline character (`\n`) at the end of your output for proper formatting.
4. **Debugging Tip**: If your output doesn't look right, check for off-by-one errors in your loop conditions or missing newline characters.