# Git Notes

## Basic Commands

### Configuration
- `git config --global user.name "Your Name"`: Set the name that will be attached to your commits.
- `git config --global user.email "your.email@example.com"`: Set the email that will be attached to your commits.

### Repository Setup
- `git init`: Initialize a new Git repository.
- `git clone <repository-url>`: Clone an existing repository.

### Basic Workflow
- `git status`: Show the working directory status.
- `git add <file>`: Add a file to the staging area.
- `git commit -m "commit message"`: Commit changes with a message.
- `git push`: Push changes to the remote repository.
- `git pull`: Fetch and merge changes from the remote repository.

### Branching
- `git branch`: List all branches.
- `git branch <branch-name>`: Create a new branch.
- `git checkout <branch-name>`: Switch to a branch.
- `git merge <branch-name>`: Merge a branch into the current branch.

### Viewing History
- `git log`: Show commit logs.
- `git log --oneline`: Show commit logs in a compact format.

### Undoing Changes
- `git reset <file>`: Unstage a file.
- `git checkout -- <file>`: Discard changes in the working directory.
- `git revert <commit>`: Create a new commit that undoes the changes from a previous commit.

### Remote Repositories
- `git remote -v`: List remote repositories.
- `git remote add <name> <url>`: Add a new remote repository.
- `git fetch <remote>`: Fetch changes from a remote repository.

## Tips
- Use meaningful commit messages.
- Commit often with small, logical changes.
- Keep your branches up to date with `git pull` or `git fetch`.

## Resources
- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)