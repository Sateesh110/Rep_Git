# Git - Local

## Workflow: GIT working >> Git staging >> GIT repository  >> GIT remote repository
```
git staging: git add <file name>
git repository: git commit
git remote repository:git push origin master
```
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
## Show Changes From A Particular Commit
```
git show --pretty="format:" <commitID>
```
## Revert a commit with a new commit 
```
git revert <commitID>
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
or touch <filename>
git add .
git commit -m'Commit changes'
```
## List all files in a branch
```
git ls-tree --name-only -r <branch name>    
```
## List all files in git repository
```
ls
ls -al
```
## Merge Branches
```
Step1: Switch to the branch you want to pull changes into: 
       git checkout <Target Branch Name>
       
Step2: Pull changes from another branch into your branch: 
       git merge <Source Branch Name>
```
## Pull a branch from remote repository
```
git pull origin <branch name>
git pull origin master
```
## Pull all branches from remote repository
```
git pull
git fetch origin
```
## Clone remote repository to local
```
Cloning is the process of pulling down a copy of a repository stored on a server:

Step1 :Go to the parent folder of where you want to repository's folder to be in.
Step2 : git clone [url to repository's git file] [name of folder / repository you want]
```
## View unstagged changes
```
git diff
```
## Unstage a file
```
git reset <file name>
```
## Undo Last Commit, Move Commits Changes To Staging
```
git reset --soft HEAD^
```
## Undo Last Commit, Remove All Changes In Your Working Directory
```
git reset --hard HEAD^
```
## Create alias command "hist" to view the history
```
git config --global alias.hist "log --oneline --graph --decorate --all"
For entire git repository: git hist
For a particular file: git hist --<filename>
```
## Rename a file name in git
```
Step1: git mv <old example.txt> <new demo.txt>
Step2: git status
Step3: ls
Step4: git commit -m"renamed the example to demo"
```
## Delete a file in git
```
Step1: git rm <file name>
Step2: git status
Step3: ls
Step4: git commit -m" deleted the file name"
```


