Git Demo

# Commands

```
git init: turns folder int a git folder

git status: get status of the git folder

git add <file> adds file to be commited

git commit -m "message"

clear to empty terminal

git log 

git remote add origin <url>

git branch

git checkout -b <branch_name>

git merge  <branch_name> merges the specific branch with the branch you are currently in 

git reset --hard goes to the last id (destructive)

git push origin <branch_name> --force  force a push (destructive)
```
Common Commands
```
git add -A              # Add all files
```
## First Time Setup Process
1. Create a new repository on GitHub
    - ``` git init```
2. Create and add an ignore file
    - ``` touch .gitignore```
    - ```git add .gitignore```
3. Commit the changes
    - ``` git commit -m "Initial commit" ```
4. Add the remote repository
    - ``` git remote add origin <url>```
5. Push the changes to the remote repository
    - ``` git push origin <branch_name>```

## Continuing to use Git Notes
- ```git add -A```
- ```git commit -m "message"```
- ```git merge <branch_name>```
- ```git push origin <branch_name>```
- ```git push origin --tags```
- ``` git push origin <branch_name> --force```