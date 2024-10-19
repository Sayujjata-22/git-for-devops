# Git Commands

## 1. Basic Setup
- **Initialize a Git repository**  
  ```bash
  git init
Check current directory
bash
Copy code
pwd
List directory contents
bash
Copy code
ls
Create a new directory
bash
Copy code
mkdir <directory-name>
Change to a directory
bash
Copy code
cd <directory-name>
2. File Operations
Create a new file
bash
Copy code
touch <file-name>
Edit a file using Vim
bash
Copy code
vim <file-name>
Display the contents of a file
bash
Copy code
cat <file-name>
Delete a file
bash
Copy code
rm <file-name>
3. Git Status and Log
Check the current Git status
bash
Copy code
git status
View commit history
bash
Copy code
git log
View commit history (oneline format)
bash
Copy code
git log --oneline
4. Staging and Committing
Stage a file for commit
bash
Copy code
git add <file-name>
Unstage a file (remove from index)
bash
Copy code
git rm --cached <file-name>
Commit staged changes
bash
Copy code
git commit -m "<commit-message>"
5. Branching
List all branches
bash
Copy code
git branch
Create and switch to a new branch
bash
Copy code
git checkout -b <branch-name>
Switch to an existing branch
bash
Copy code
git checkout <branch-name>
6. Undo Changes
Restore a file to the last committed state
bash
Copy code
git restore <file-name>
7. Miscellaneous
Clear terminal screen
bash
Copy code
clear
Show command history
bash
Copy code
history
