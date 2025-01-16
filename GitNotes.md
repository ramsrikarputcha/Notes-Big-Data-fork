# Git Notes

## Introduction to Git
Git is a distributed version control system that helps developers collaborate on projects. It allows you to track changes, revert to previous stages, and work on multiple branches simultaneously.
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Basic Commands

### Configuration
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Initializing a Repository
```sh
git init
```

### Cloning a Repository
```sh
git clone <repository-url>
```

### Checking Status
```sh
git status
```

### Adding Changes
```sh
git add <file>
git add .
```

### Committing Changes
```sh
git commit -m "Commit message"
```

### Viewing Commit History
```sh
git log
```

### Pushing Changes
```sh
git push origin <branch-name>
```

### Pulling Changes
```sh
git pull origin <branch-name>
```

## Branching and Merging

### Creating a New Branch
```sh
git branch <branch-name>
```

### Switching Branches
```sh
git checkout <branch-name>
```

### Merging Branches
```sh
git merge <branch-name>
```

### Deleting a Branch
```sh
git branch -d <branch-name>
```

## Undoing Changes

### Unstaging a File
```sh
git reset <file>
```

### Reverting a Commit
```sh
git revert <commit-id>
```

### Resetting to a Previous Commit
```sh
git reset --hard <commit-id>
```

## Remote Repositories

### Adding a Remote
```sh
git remote add origin <repository-url>
```

### Viewing Remotes
```sh
git remote -v
```

### Removing a Remote
```sh
git remote remove <name>
```

## Tips and Tricks

- Use `git stash` to save changes temporarily.
- Use `git rebase` to clean up commit history.
- Use `.gitignore` to exclude files from being tracked.

## Resources
- [Official Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
