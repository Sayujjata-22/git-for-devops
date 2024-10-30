
## Basic Commands
- **Initialize a Git Repository**
  ```bash
  git init
  ```

- **Check Status of Files**
  ```bash
  git status
  ```

- **List Files**
  ```bash
  ls
  ls -l
  ls -a
  ```

## Working with Files
- **Create Files**
  ```bash
  touch file1.txt file2.txt
  ```

- **Edit Files (using Vim)**
  ```bash
  vim hello-world.txt
  vim hello.txt
  vim file1
  vim file2.txt
  ```

- **View File Contents**
  ```bash
  cat hello-world.txt
  cat hello.txt
  cat file1
  ```

- **Remove Files**
  ```bash
  rm hello-world.txt
  rm hello.txt
  rm file2.txt
  ```

- **Untrack a File without Deleting**
  ```bash
  git rm --cached file1.txt
  ```

## Staging and Committing Changes
- **Stage Files for Commit**
  ```bash
  git add hello.txt
  git add file1.txt file2.txt
  git add file3.txt
  git add file1
  ```

- **Commit Changes**
  ```bash
  git commit -m "adding file1 and file2"
  git commit -m "adding hello"
  git commit -m "adding updated version of file"
  git commit -m "added new file file1"
  git commit -m "adding new file from dev branch"
  ```

## Branching and Switching
- **Create and Switch to a New Branch**
  ```bash
  git checkout -b dev
  git checkout -b master
  git checkout -b from-dev
  git checkout -b from-master
  ```

- **Switch Between Branches**
  ```bash
  git checkout dev
  git checkout master
  git switch master
  git switch dev
  ```

## Viewing Project History
- **View Commit Log**
  ```bash
  git log
  git log --oneline
  git logs
  ```

- **View Branches**
  ```bash
  git branch
  ```

## Miscellaneous Commands
- **Clear Terminal**
  ```bash
  clear
  ```

- **Print Working Directory**
  ```bash
  pwd
  ```

## Additional Commands
- **Create a Directory for Project**
  ```bash
  mkdir git-for-devops
  ```
