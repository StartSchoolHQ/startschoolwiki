---
sidebar_label: 'Quest02'
sidebar_position: 2
---

# Python Quest02 - Control Flow & Functions

Welcome to Python Quest02! This quest will introduce you to fundamental programming concepts including conditional statements, functions, loops, and return values. Let's master these building blocks of Python programming!

## 🚀 Key Features
- **Control Flow**: Learn to make decisions in your code using if statements
- **Functions**: Create reusable blocks of code
- **Loops**: Implement repetitive tasks efficiently
- **Parameters**: Pass data to functions
- **Return Values**: Get results back from functions

## 📝 Task Requirements

1. **Proper File Structure**:
   - Each exercise must be in its own directory (ex00, ex01, etc.)
   - File names must match exactly as specified
   - No additional files should be included

2. **Code Style**:
   - Follow Python indentation rules (4 spaces)
   - Use clear and readable code
   - No unnecessary comments or debug prints

3. **Function Requirements**:
   - Functions must be defined exactly as specified
   - Parameter names and types must match requirements
   - Return values must be of the correct type

## ⚠️ Common Pitfalls & Solutions

### Ex00: my_first_if_multiple_conditions
- Remember to use logical operators:
  - `and` for AND conditions
  - `or` for OR conditions
  - Use parentheses to group conditions
- Test all conditions independently first

### Ex01: my_first_function
- Function definition syntax:
  ```python
  def function_name():
      # code here
  ```
- Don't forget the colon `:` after function name
- Proper indentation is crucial

### Ex02: my_first_while
- Remember to:
  - Set a condition that will eventually be false
  - Increment your counter
  - Check your loop condition carefully
- Common mistakes:
  - Forgetting to increment index
  - Wrong comparison operator

### Ex03: my_first_param_function
- Function parameters go in parentheses
- String concatenation with numbers:
  - Convert numbers to strings using `str()`
- Remember to decrement the counter

### Ex04: my_first_return_function
- Use the `return` keyword
- Function can end early with return
- Return statement needs no parentheses

## 🛠️ Useful Resources

### Documentation
- [Python Official Documentation - Control Flow](https://docs.python.org/3/tutorial/controlflow.html)
- [Python Official Documentation - Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

### Exercise-Specific Tips

#### For Multiple Conditions (ex00)
```python
# Example of multiple conditions
if (condition1 and condition2 and condition3):
    # code here
```

#### For Functions (ex01)
```python
# Basic function structure
def function_name():
    # code here
```

#### For Loops (ex02)
```python
# While loop structure
while condition:
    # code here
    # don't forget to update condition
```

#### For Parameters (ex03)
```python
def function_name(parameter):
    print(str(parameter))  # convert to string for printing
```

#### For Return Values (ex04)
```python
def function_name():
    return value  # immediately exits function
```

### General Tips
1. Test your code thoroughly before submitting
2. Use print statements to debug
3. Check your syntax carefully
4. Verify all requirements are met
5. Test edge cases when applicable
