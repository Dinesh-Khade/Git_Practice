# Git Commands Reference

## Configuring Git
- **Set user name**: `git config --global user.name "Your Name"`
- **Set email**: `git config --global user.email "youremail@example.com"`
- **View Git configuration**: `git config --list`

## Initialize a Repository
- **Initialize a new Git repository**: `git init`
- **Clone an existing repository**: `git clone <repository-url>`

## Basic Snapshotting
- **Check the current status**: `git status`
- **Add files to the staging area**: `git add <file>`
- **Commit changes**: `git commit -m "Commit message"`
- **Add and commit changes**: `git commit -am "Commit message"`
- **Remove files from staging area**: `git reset <file>`

## Branching and Merging
- **Create a new branch**: `git branch <branch-name>`
- **Switch to a branch**: `git checkout <branch-name>`
- **Create and switch to a new branch**: `git checkout -b <branch-name>`
- **List all branches**: `git branch`
- **Merge a branch into the current branch**: `git merge <branch-name>`
- **Delete a branch**: `git branch -d <branch-name>`

## Remote Repositories
- **Add a remote repository**: `git remote add origin <repository-url>`
- **List all remotes**: `git remote -v`
- **Push changes to a remote repository**: `git push origin <branch-name>`
- **Pull changes from a remote repository**: `git pull origin <branch-name>`

## Stashing
- **Stash uncommitted changes**: `git stash`
- **View all stashes**: `git stash list`
- **Apply a stash**: `git stash apply`
- **Delete a stash**: `git stash drop`

## Viewing History
- **View commit history**: `git log`
- **View a single commit**: `git show <commit-id>`
- **View changes made to a file**: `git diff <file>`

## Tags
- **Create a tag**: `git tag <tag-name>`
- **List all tags**: `git tag`
- **Push a tag to a remote repository**: `git push origin <tag-name>`
