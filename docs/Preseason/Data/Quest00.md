---
sidebar_label: 'Quest 00'
sidebar_position: 2
---

#  Quest00: Shell Environment Basics

## 🚀 Key Features 

- **File Operations**: Create and manipulate files using shell commands
- **Permissions Management**: Learn to modify file permissions using chmod
- **Git Workflow**: Practice basic Git operations
- **Archive Creation**: Learn to use the tar command
- **Shell Scripting**: Introduction to basic shell output

## 📝 Task Requirements

1. **Directory Structure**: Each exercise must be in its own directory (ex00, ex01, etc.)
2. **Git Usage**: Every exercise must be committed and pushed to Git
3. **File Naming**: Exact file names must be followed as specified in each exercise
4. **No Test Files**: Do not include any test files in your submissions
5. **Gandalf Testing**: All exercises must pass the gandalf test

## 🛠️ Useful Resources

### Websites/Videos and Documentation

1. **Videos**
    - [Bash Tutorial](https://www.youtube.com/watch?v=BFMyUgF6I8Y)

2. **Git Resources**
    - [Git Official Documentation](https://git-scm.com/doc)
    - [GitHub Git Guides](https://github.com/git-guides) 
    - [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials) 
    - [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

### General Commands
```bash
# File operations
touch filename     # Create empty file
echo "text" > file # Create file with content
ls -l             # List files with details
chmod xxx file    # Change file permissions

# Directory operations
mkdir dirname     # Create directory
cd dirname        # Change directory
pwd              # Print working directory
```

### Git Commands
```bash
git add filename     # Stage file
git commit -m "msg"  # Commit with message
git push            # Push to repository
git status          # Check repository status
```

### File Permission Tips
- Permission format: `rwxrwxrwx` (user/group/others)
- Convert permissions to numeric:
    - r (read) = 4
    - w (write) = 2
    - x (execute) = 1
    - Example: rwxr-xr-- = 754


### Exercise-Specific Tips

#### Ex00: My First File
- Use `touch` to create empty file
- Verify with `ls`

#### Ex01: File With Content
- Create 40 characters of content
- Verify size with `ls -l`

#### Ex02: File With Permissions
1. Create file and add content first
2. Change permissions after content
3. Create tar archive last

#### Ex03: Git Operations
- Follow commands in exact order
- Ensure new line at end of file

#### Ex04: My Z
- File should output single 'Z' with newline
- Test using `cat` command