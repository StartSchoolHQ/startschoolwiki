---
sidebar_label: '(exercise) my_strchr'
sidebar_position: 10
---

# my_strchr

In this exercise, you will implement a function that searches for the first occurrence of a given character in a string. If the character is found, the function returns a pointer to the first matching character in the string. If no match is found, the function returns `NULL`.

## 🚀 Key Features

- **String Traversal**: Iterate through a string to find a specific character.
- **Pointer Arithmetic**: Return a pointer to the matching character in the string.
- **Null Handling**: Ensure correct handling of null characters and return values.

## 📝 Task Requirements
1. **Gandalf Testing**: All exercises must pass the gandalf test

---

## 🛠️ Useful resources for accomplishing this task

### Pointer Basics
- [Pointers in C](https://www.geeksforgeeks.org/pointers-in-c-and-c-set-1-introduction-arithmetic-and-array/)
- Use pointers to traverse a string and locate specific characters.

### String Basics
- [Strings in C](https://www.tutorialspoint.com/cprogramming/c_strings.htm)
- Strings are null-terminated, meaning they end with the `'\0'` character.

---

## 🧪 Test Cases

| Input String   | Input Character | Expected Output | Explanation                                |
|----------------|-----------------|-----------------|--------------------------------------------|
| `"abcabc"`     | `'b'`           | `"bcabc"`       | First `'b'` found at index 1, return from there. |
| `"121212"`     | `'2'`           | `"21212"`       | First `'2'` found at index 1, return from there. |
| `"abc"`        | `'d'`           | `NULL`          | `'d'` is not in the string, return `NULL`. |
| `"hello\0"`    | `'\0'`          | `"\0"`          | Null character matches the end of the string. |
| `""`           | `'a'`           | `NULL`          | Empty string cannot contain any character. |

---

## 💡 Tips for Beginners
1. **Null-Terminated Strings**: Remember that strings in C end with a `'\0'` character. Include it in your comparisons.
2. **Pointer Arithmetic**: Increment the pointer to traverse the string.
3. **Edge Cases**: Consider scenarios like empty strings and null characters in your implementation.
4. **Debugging Tip**: Use `printf` to print pointer values and characters during traversal to ensure correctness.