---
sidebar_label: 'My Cat'
sidebar_position: 3
---


# My Cat


> It's your turn to code the software cat!
>
> Create a program called my_cat which does the same thing as the system's cat command used in the command-line.
> 
> Your program should read the content of each files which are received as an argument to your software.
> Unlike the real Cat command, you don't have to handle any options. :-)

## 🚀 Key Features

- **Process program arguments**: It is required to use the command arguments for giving file paths to the program.
- **Read files from path**: Open the file for reading. Remember to close it afterwards.
- **Print out file contents**: Simply print out all text inside the open file.
- **[OPTIONAL] Handle Errors**: A good practice would be to handle the exceptions in the cases of typos in file names and when trying to print missing files.
In such cases, an exception will be thrown, which should be handled inside code. That said, gandalf does not test for this in this task. 

## Notes
- This task repeats in multiple tracks. It is not required to redo it each time, but it is good practice.

## 📝 Game Rules/Task Requirements (Gandalf test requirements)

Gandalf does not have specific requirements for this task. Remember to not pass non-code files to git, to prevent errors from gandalf.

1. **Test 1**: Opens single file named 'blah1'
2. **Test 2**: Opens single file named 'blah2'
2. **Test 3**: Opens two files named 'blah2' & 'blah3'

## ⚙️ How the Program Works (Only if a project, not for quests or exercises)

This is simple, you've got this (Hint: print everything you read).

## ⚠️ Error Handling

- Simple try-except wrap for the file reading

## 🛠️ Useful resources for accomplishing this task
* man cat - linux manual for cat program, reference it if any further details on the program are required. Link : [Cat description from linux manual](https://www.man7.org/linux/man-pages/man1/cat.1.html)