---
sidebar_label: 'My Printf'
sidebar_position: 4
description: A guide to creating a custom print function similar to printf in C.
---

# My_printf

Welcome to the **My_printf Project**, where you will create your own version of the `printf` function in C. This project will help you understand variadic functions and improve your coding skills.

## 🚀 Key Features

- **Custom Output Control**: Recreate the core functionality of `printf` to format and display output.
- **Support for Various Data Types**: Handle integers, characters, strings, and pointers.
- **No Global or Static Variables**: Promote code purity and organization.

## 📝 Function Description

The `my_printf` function produces output according to a specified format. Here's how it works:

- **Format String**: It consists of regular characters and conversion specifications that start with the `%` character. 
- **Conversion Options**:
  - `%d`, `%o`, `%u`, `%x`: Convert an integer to signed decimal, unsigned octal, unsigned decimal, and unsigned hexadecimal.
  - `%c`: Convert an integer to an unsigned char and display it.
  - `%s`: Print characters from a string until a null character is reached.
  - `%p`: Print a pointer in hexadecimal format.

## ⚙️ Requirements

- **Compilation Flags**: Your code should be compiled with `-Wall -Wextra -Werror`.
- **Memory Management**: Be careful of memory leaks; you can use debugging tools to check for errors.
- **No Global or Static Variables**: Only use local variables within your functions.

## ⚠️ Unauthorized Functions

- The standard `printf` and related functions (like `fprintf`, `sprintf`, etc.) are not allowed.
- Multiline macros and including another `.c` file are strictly forbidden.
- Logic-based macros (like while or if) are not permitted.

## 🛠️ Example Usage

You would compile and run your program as follows:

```bash
gcc -Wall -Wextra -Werror my_printf.c -o my_printf
./my_printf "Hello, %s! Your score is %d." "Alice" 95
```

## 🤔 Final Notes

If you encounter issues, don't hesitate to reach out for help. Good luck with your coding journey!