# Git and GitHub notes/cheatsheet
## Basic Git Commands

| Command | Description |
|---------|------------|
| `git init` | Initialize a new Git repository |
| `git clone <repo-url>` | Clone a repository from GitHub or another remote source |
| `git status` | Check the current state of your repo (changes, staged files, etc.) |
| `git add <file>` | Stage a file for commit |
| `git add .` | Stage all changed files for commit |
| `git commit -m "message"` | Commit changes with a message |
| `git log` | View commit history |
| `git branch` | List all branches |
| `git branch <branch-name>` | Create a new branch |
| `git checkout <branch-name>` | Switch to another branch |
| `git checkout -b <branch-name>` | Create and switch to a new branch |
| `git merge <branch-name>` | Merge a branch into the current branch |
| `git pull` | Fetch changes from the remote repository and merge |
| `git push` | Push committed changes to the remote repository |
## 🔹 Working with Remote Repositories
| Command | Description |
|---------|------------|
| `git remote -v` | List all remote repositories |
| `git remote add origin <url>` | Add a remote repository |
| `git push -u origin <branch>` | Push changes and set upstream branch |
| `git fetch` | Fetch latest changes from the remote repository |
| `git pull origin <branch>` | Pull latest changes from a specific branch |