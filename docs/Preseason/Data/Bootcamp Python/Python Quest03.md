---
sidebar_label: 'Quest03'
sidebar_position: 3
---

# Python Quest03 - Basic Functions and Arguments

Welcome to Python Quest03! This quest focuses on fundamental Python concepts including command-line arguments, conditional statements, basic arithmetic operations, and string formatting. You'll learn how to create simple functions that handle different data types and perform various operations.

## 🚀 Key Features
- **Command Line Arguments**: Learn to handle script parameters using sys.argv
- **Conditional Statements**: Practice if-else conditions with number comparison
- **Basic Math Operations**: Implement fundamental arithmetic operations
- **String Formatting**: Create formatted strings with multiple variables
- **Return Values**: Understanding function returns in Python

## 📝 Task Requirements
1. **File Structure**: Ensure correct file names and directory structure for each exercise
2. **Function Prototypes**: Follow the exact function signatures provided
3. **Return Types**: Match the specified return types (integers, strings, etc.)
4. **Parameter Types**: Handle parameters according to their specified types
5. **Testing Requirements**: Comment out all function test calls before submission

## ⚙️ Exercise Breakdown

### Ex00: my_first_script_with_args.py
- Use `sys.argv` to access command-line arguments
- Remember that `sys.argv[0]` is the script name
- Print each argument on a new line using loop

### Ex01: my_is_negative.py
- Return 1 for positive numbers or zero
- Return 0 for negative numbers
- Use simple if-else structure

### Ex02: my_abs.py
- Return absolute value without using abs()
- Handle both positive and negative integers
- Consider zero case

### Ex03-Ex05: Basic Arithmetic
- my_add.py: Addition operation
- my_sub.py: Subtraction operation
- my_mult.py: Multiplication operation
- Handle positive and negative integers
- Consider edge cases (zero, large numbers)

### Ex06: my_string_formatting.py
- Use string formatting to combine variables
- Include proper spacing between words
- Add newline at the end of output

## ⚠️ Common Pitfalls
- Forgetting to import sys for argv
- Not commenting out test calls
- Missing newline in string formatting
- Incorrect handling of negative numbers
- Wrong return type (int vs string)

## 🛠️ Useful Resources

### Documentation and References
- [Python Command Line Arguments](https://docs.python.org/3/library/sys.html#sys.argv)
- [Python String Formatting](https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals)
- [Python Conditional Statements](https://docs.python.org/3/tutorial/controlflow.html#if-statements)

### Exercise-Specific Tips

#### For my_first_script_with_args.py:
```python
import sys
# sys.argv[1:] gives all arguments except the script name
```

#### For String Formatting:
```python
# f-strings are readable and efficient
```

### Testing Tips
1. Test with edge cases (0, negative numbers, large numbers)
2. Verify newline characters where required
3. Check return types match specifications
4. Test with various argument combinations
5. Remember to comment out test calls before submission