# Git Test Repository

This repository was created to understand and practice Git and GitHub basics.

## Purpose
- Learn Git installation and configuration on Windows
- Understand basic Git workflow (init, add, commit, push)
- Connect a local repository to GitHub

---

## Tools Used
- Git for Windows
- Git Bash
- GitHub
- Visual Studio Code

---

## Commands Used (Reference)

### 1. Configure Git user (one-time setup)
```bash
git config --global user.name "Prem Arun P"
git config --global user.email "premarun375@gmail.com"
 

2. Create project directory

mkdir git-test
cd git-test

3. Initialize Git repository

git init

4. Create README file

echo "My first GitHub repository" > README.md

5. Check repository status

git status

6. Stage files

git add .

7. Commit changes

git commit -m "Initial commit"

8. Rename default branch to main

git branch -M main

9. Add GitHub remote repository

git remote add origin https://github.com/premarun37/git-test.git

10. Verify remote connection

git remote -v

11. Push code to GitHub

git push -u origin main
