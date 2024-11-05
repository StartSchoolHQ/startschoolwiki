---
sidebar_label: 'Quest 06'
sidebar_position: 7
---

# Python Quest06

In this quest, you will delve into data parsing, transformation, and processing using Python. You will work with CSV files, manipulate data, and ensure your solutions meet specific formatting requirements. This quest will enhance your skills in handling real-world data and preparing it for further analysis.

## 🚀 Key Features

- Parsing CSV files without external libraries
- Transforming data using the `datetime` library
- Processing data and formatting output to meet specific requirements
- Working with Python dictionaries and string manipulation

## 📝 Task Requirements

1. **Directory Structure**: Each exercise must be in its own directory (ex00, ex01, etc.)
2. **Git Usage**: Every exercise must be committed and pushed to Git
3. **File Naming**: Exact file names must be followed as specified in each exercise
4. **No Test Files**: Do not include any test files in your submissions
5. **Gandalf Testing**: All exercises must pass the gandalf test

## 🛠️ Useful Resources for Accomplishing This Task
- [What is a CSV file format?](https://www.geeksforgeeks.org/csv-file-format/)

### Exercise-Specific Tips

#### Ex00 - My Csv Parser

In the task descriptions, it doesn't explicitly state how to parse CSV. You might use libraries for it, but you can also do it without them. Rows are separated by a new line `\n`, and column values are separated by a comma `,`.

- [split()](https://www.w3schools.com/python/ref_string_split.asp) e.g., when splitting CSV by new line or comma separator.
- [rstrip()](https://www.w3schools.com/python/ref_string_rstrip.asp) e.g., when removing trailing new line separator.

Make sure you are splitting with the correct separators. You must return an array of arrays.

#### Ex01 - My Data Transform

Rows are separated by a new line `\n`, and column values are separated by a comma `,`.

- As the exercise description states, you can use the `datetime` library. More details [here](https://www.geeksforgeeks.org/python-datetime-strptime-function/) and [here](https://www.dataquest.io/blog/python-datetime/). After parsing a string to a datetime object, it can be handy to narrow it down to a time object and use it for comparison in conditional statements.
- [How to convert a string into an integer in Python](https://www.datacamp.com/tutorial/how-to-convert-a-string-into-an-integer-in-python)
- [Python array add](https://www.w3schools.com/python/gloss_python_array_add.asp)
- [Python string join method](https://www.geeksforgeeks.org/python-string-join-method/)

#### Ex02 - My Data Process

Useful links:
- [Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp)

In order to satisfy Gandalf, you must do some extra work, instead of just returning your output dictionary.
```python
def my_data_process(input):
    output = {}  # where output is going to be set after logic is executed

    # TODO: process logic here

    # NOT: return output
    return str(output).replace(", ", ",").replace(": ", ":").replace("'", '"')
```