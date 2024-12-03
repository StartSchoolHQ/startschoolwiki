---
sidebar_label: '(exercise) my_string_formatting'
sidebar_position: 11
---

# my_string_formatting

In this exercise, you will implement a function that formats and prints a greeting string using three inputs: first name, last name, and age. The output should follow a specific format and include a newline at the end.

## 🚀 Key Features

- **String Formatting**: Combine multiple inputs into a formatted string.
- **Print Output**: Output the formatted string to the console.
- **Input Handling**: Handle a mix of string and integer inputs.

## 📝 Task Requirements

1. **Gandalf Testing**: All exercises must pass the gandalf test

---

## 🛠️ Useful resources for accomplishing this task

### String Formatting in C
- [printf Function in C](https://www.tutorialspoint.com/c_standard_library/c_function_printf.htm)
- The `printf` function is used for formatted output.
  - `%s` is used for strings.
  - `%d` is used for integers.
  - Remember to include a newline (`\n`) at the end.

### Character Strings
- [Strings in C](https://www.geeksforgeeks.org/strings-in-c/)
- Strings are arrays of characters in C and must be null-terminated (`\0`).

---

## 🧪 Test Cases

| First Name | Last Name | Age | Expected Output                          |
|------------|-----------|-----|------------------------------------------|
| `"john"`   | `"doe"`   | `37`| `Hello, my name is john doe, I'm 37.`   |
| `"Baby"`   | `"Yoda"`  | `50`| `Hello, my name is Baby Yoda, I'm 50.`  |
| `"Marie"`  | `"Curie"` | `26`| `Hello, my name is Marie Curie, I'm 26.`|

---

## 💡 Tips for Beginners
1. **Use `printf` Correctly**: Ensure you use the correct format specifiers (`%s` for strings, `%d` for integers) to avoid errors.
2. **Include Newline**: Always add a newline character at the end of the output for proper formatting.
3. **Debugging Tip**: Test your function with different names and ages to ensure the formatting is consistent.