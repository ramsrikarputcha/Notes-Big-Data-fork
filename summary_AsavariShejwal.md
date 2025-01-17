# Git Notes

## Introduction to Git

Git is a distributed version control system that allows multiple developers to collaborate on a project. It tracks changes to files and allows you to easily revert to previous versions if needed.

## Basic Git Commands

- `git init`: Initializes a new Git repository in the current directory.
- `git add <file>`: Adds a file to the staging area.
- `git commit -m "<message>"`: Commits the changes in the staging area with a descriptive message.
- `git status`: Shows the current status of the repository.
- `git log`: Displays the commit history.

## Branching and Merging

- `git branch`: Lists all branches in the repository.
- `git branch <branch-name>`: Creates a new branch.
- `git checkout <branch-name>`: Switches to the specified branch.
- `git merge <branch-name>`: Merges the specified branch into the current branch.

## Remote Repositories

- `git remote add <name> <url>`: Adds a remote repository.
- `git push <remote> <branch>`: Pushes the local branch to the remote repository.
- `git pull <remote> <branch>`: Fetches changes from the remote repository and merges them into the current branch.

## Undoing Changes

- `git reset <commit>`: Discards commits, moving the branch pointer to a previous commit.
- `git revert <commit>`: Creates a new commit that undoes the changes made in the specified commit.

## Conclusion

These are just some of the basic Git commands. Git offers many more features and options to manage your codebase effectively. It's recommended to explore the official Git documentation for more in-depth information.