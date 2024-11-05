---
sidebar_label: 'Quest 05'
sidebar_position: 6
---

# Python Quest05

In this quest you will enhance your skills in string manipulation, loops, and array handling by implementing various functions. Each task focuses on a specific operation, such as iterating through arrays, modifying elements, or checking conditions. You will create functions to print array elements, multiply array values, count string lengths, remove duplicates, and check if arrays are sorted.

## 🚀 Key Features

- **Working with strings**: Manipulate strings and their characters, such as casing and calculating the length.
- **Working with loops and indexes** : Iterate over arrays and keep index counters.

## 📝 Task Requirements

1. **Directory Structure**: Each exercise must be in its own directory (ex00, ex01, etc.)
2. **Git Usage**: Every exercise must be committed and pushed to Git
3. **File Naming**: Exact file names must be followed as specified in each exercise
4. **No Test Files**: Do not include any test files in your submissions
5. **Gandalf Testing**: All exercises must pass the gandalf test

## 🛠️ Useful resources for acomplishing this task

### Working arrays and strings

It's not explicitly prohibited to use `len()` and other in-built functions, decide for yourself.

- [foreach loop](https://www.geeksforgeeks.org/python-foreach-how-to-program-in-python/)
- [while loop](https://www.geeksforgeeks.org/python-while-loop/)


### Exercise-Specific Tips

#### Ex03: My Array Uniq
As an inspiration, it might be a good time to discover other collection types in python, such as - [sets](https://www.geeksforgeeks.org/sets-in-python/).

#### Ex04: My Is Sort
Advice for Writing a Function to Check if an Array is Sorted:
1. Understand Sorting Orders:
    - Ascending Order: Each element is less than or equal to the next.
    - Descending Order: Each element is greater than or equal to the next.
2. Edge Cases:
    - Arrays with 0 or 1 element are always considered sorted.
    - Arrays with all identical elements are sorted in both ascending and descending orders.
3. Iterate Through the Array:
    - Use a loop to compare each element with the next one.
    - For ascending order, check if the current element is greater than the next.
    - For descending order, check if the current element is less than the next.
4. Early Exit:
    - If any comparison fails, return False immediately to save time.
5. Combine Checks:
    - Check for both ascending and descending orders and return True if either condition is met.