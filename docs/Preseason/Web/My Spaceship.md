---
sidebar_label: 'My Spaceship'
sidebar_position: '4'
---

# My Spaceship `JavaScript`

Welcome to the **My Spaceship** project of **Preseason Web** track! Here you will practice writing complex conditional statements and work with computer graphics coordinate system.

## 🚀 Key Features

- **Coordinate System**: Understand how [Computer Graphics Coordinate System](https://fcs-cs.github.io/cs1-2018/modules/01-introduction/computer-coordinates/) work & practice manipulating x, y coordinates.
- **Array methods**: Learn to manipulate JavaScript arrays using different methods.
- **String methods**: Learn to modify JavaScript strings using different methods.
- **Conditional logic**: Practice writing complex conditional statements that represent your program's logic.
- **Writing ReadMe**: Practice writing a ReadMe file describing the project & your solution.

## 📝 Game Rules/Task Requirements

1. **Directory Structure**: For this project, create a folder `ex00` where the source code of your project is stored.
2. **Git**: Git add, git commit & git push the final project and any major changes you make.
3. **File Naming**: Use specific name for the source file provided under `submit file`.
4. **Testing**: **NO** tests should be provided in the source code.
5. **Gandalf Testing**: The project must pass all Gandalf tests.
6. **ReadMe File**: It is mandatory to submit a ReadMe file & fill each section with the minimum of 30 characters.

## ⚙️ How the Program Works

❗The spaceship starts at (0, 0) and faces upward.

### Input

**String of letters representing a planned flight.**  
Movement options are `R` (Right), `L` (Left), `A` (advance).

### Return Value (output)

**Spaceship's final destination & orientation relative to the starting point.**  
Program's output follows this format: `"{x: X, y: Y, direction: 'DIRECTION'}"`

### Interpreting the flight path

Based on the user input, the program updates the spaceship's direction & position:
- `R` turns the spaceship to the right.
- `L` turns the spaceship to the left.
- `A` moves the spaceship by 1 in the current direction.

### Changing the direction

Unlike the *Cartesian Coordinate System* that we all are (hopefully) familiar with, *Computer Graphics Coordinate System*'s starting point is at the **top-left** corner of the screen. This way:
- `Up` decreases the `y` coordinate
- `Right` increases the `x` coordinate
- `Down` increases the `y` coordinate
- `Left` decreases the `x` coordinate

### Example

```
Input: "RAARA"
Output: 
Return Value: "{x: 2, y: 1, direction: 'down'}"
```

## ⚠️ Error Handling

When coding the program, watch out for common issues that cause errors:
- **Invalid type**: Input passed to the function must be a type of `string`.
- **Invalid characters**: Input passed to the function must only contain valid commands such as `R`, `L` and `A`.
- **Case Sensitivity**: Input passed to the function must handle both `lowercase` & `uppercase`. 

## 🛠️ Useful resources for acomplishing this task

### String Interpolation
- [**String Interpolation Explained**](https://www.geeksforgeeks.org/string-interpolation-in-javascript/)
- [**String Interpolation (with Use Cases)**](https://favtutor.com/articles/string-interpolation-javascript/)

### Coordinate System
- [**The difference between Cartesian coordinates and screen coordinates**](https://www.vaia.com/en-us/textbooks/computer-science/fundamentals-of-java-ap-computer-science-4-edition/chapter-5/problem-1-describe-the-difference-between-cartesian-coordina/#:~:text=The%20main%20difference%20is%20in,the%20y%2Daxis%20increases%20downwards.)

### Conditional Logic
- [**How To Use the Switch Statement**](https://www.digitalocean.com/community/tutorials/how-to-use-the-switch-statement-in-javascript)
- [**Switch Case vs. If-Else Explained**](https://builtin.com/articles/switch-case-vs-if-else)

### Array & String Methods
- **Array Methods [Cheat Sheet 1](https://clubmate.fi/array-cheat-sheet) & [Cheat Sheet 2](https://array-methods.github.io/)**
- [**String Methods Cheat Sheet**](https://techtalkbook.com/string-methods-cheatsheet-in-javascript/)

### Practice Platforms
- [**CodeWars**](https://www.codewars.com/)
- [**Exercism**](https://exercism.org/)
- [**JSchallenger**](https://jschallenger.com/)
- [**Edabit**](https://edabit.com/)
- [**LeetCode**](https://leetcode.com/)

### Advice for completing the tasks
1. Make sure to put a semicolon `;` after each JavaScript statement.
2. Make sure to save `Ctrl + S` minor changes & Git push major ones.
3. [Use Google to your advantage!](https://www.freecodecamp.org/news/how-to-google-like-a-pro-10-tips-for-effective-googling/) You can also check out [this](https://www.freecodecamp.org/news/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2) article on problem-solving :)