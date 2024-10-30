Basic Commands
Initialize a Git Repository git init

Check Status of Files git status

List Files ls
ls -l
ls -a

Working with Files
Create Files touch file1.txt file2.txt

Edit Files (using Vim) vim hello-world.txt
vim hello.txt
vim file1
vim file2.txt

View File Contents cat hello-world.txt
cat hello.txt
cat file1

Remove Files rm hello-world.txt
rm hello.txt
rm file2.txt

Untrack a File without Deleting git rm --cached file1.txt

Staging and Committing Changes
Stage Files for Commit git add hello.txt
git add file1.txt file2.txt
git add file3.txt
git add file1

Commit Changes git commit -m "adding file1 and file2"
git commit -m "adding hello"
git commit -m "adding updated version of file"
git commit -m "added new file file1"
git commit -m "adding new file from dev branch"

Branching and Switching
Create and Switch to a New Branch git checkout -b dev
git checkout -b master
git checkout -b from-dev
git checkout -b from-master

Switch Between Branches git checkout dev
git checkout master
git switch master
git switch dev

Viewing Project History
View Commit Log git log
git log --oneline
git logs

View Branches git branch

Miscellaneous Commands
Clear Terminal clear

Print Working Directory pwd

Additional Commands
Create a Directory for Project mkdir git-for-devops
