Git Commands for DevOps
1. Directory Management
bash
Copy code
mkdir git-for-devops  
cd git-for-devops/  
pwd  
2. File and Directory Operations
bash
Copy code
ls  
ls -a  
ls -l  
rm test.txt  
touch fileA.txt fileB.txt  
rm fileB.txt  
vim test.txt  
cat fileB.txt  
3. Git Initialization
bash
Copy code
git init  
4. Viewing Git Status
bash
Copy code
git status  
5. Staging Files
bash
Copy code
git add fileA.txt  
git add fileB.txt  
6. Unstaging Files
bash
Copy code
git rm --cached fileB.txt  
7. Committing Changes
bash
Copy code
git commit -m "adding file a & b"  
git commit -m "adding changes in file B"  
git commit -m "Added new file in dev branch"  
8. Branching Operations
bash
Copy code
git branch  
git checkout -b dev  
git checkout master  
git checkout dev  
9. Restoring and Switching Files
bash
Copy code
git restore fileB.txt  
10. Git Logs
bash
Copy code
git log  
git log --oneline  
11. Switching Branches
bash
Copy code
git switch master  
git switch dev  
