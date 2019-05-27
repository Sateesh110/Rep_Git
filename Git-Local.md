# Git - Local

## Initializing Local Repository as git repository
```
Step1: Get to the folder; right click to open git bash
Step2: git init
```
## Add a file
```
git add <filename>
```
## Add all files and folders
```
git add .
```
## Add/track one specific folder 
```
git add chapter2/
```
## Status
```
git status
```
## Commit all files 
```
git commit -m"commit changes"
```
## show all commits in the current branch’s history
```
git log
```
## List all branches in local repository
```
git branch
```
## Create a new branch
```
git branch <name of new branch>
```
## Switch to branch
```
git branch <branch name>
```
## Create a new branch n Switch
```
git branch -b <name of new branch>
```
## Create file in the new branch
```
echo "New file in Child2" > [Child2_File.txt]
git add .
git commit -m'Commit changes'
```
## List all files in a branch
```
git ls-tree --name-only -r <branch name>    
```
## Merge Branches
```
Step1: Switch to the branch you want to pull changes into: 
       git checkout <Target Branch Name>
       
Step2: Pull changes from another branch into your branch: 
       git merge <Source Branch Name>
```
## Pull changes form remote repository
```
git pull origin master
or git pull
```
## Clone remote repository to local
```
Cloning is the process of pulling down a copy of a repository stored on a server:

Step1 :Go to the parent folder of where you want to repository's folder to be in.
Step2 : git clone [url to repository's git file] [name of folder / repository you want]
```
## Clone remote repository to local
```
Cloning is the process of pulling down a copy of a repository stored on a server:

Step1 :Go to the parent folder of where you want to repository's folder to be in.
Step2 : git clone [url to repository's git file] [name of folder / repository you want]
```
