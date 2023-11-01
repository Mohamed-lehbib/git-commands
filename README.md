# git-commands
# Essential Git Commands

This document provides a list of essential Git commands that will help you to work comfortably with Git.

## Getting Started

- Initializes a new Git repository in your current working directory:
```
git init
```

## Working with Repositories

- Creates a copy of an existing Git repository from the specified URL:
```
git clone [url]
```

## Staging and Snapshotting

- Stages the specified file(s), preparing it for a commit:
```
git add [file]
```
- Takes a snapshot of the staged changes along with a descriptive message:
```
git commit -m "[commit message]"
```

## Inspection and Comparison

- Shows the current status of the repository with respect to the staging area:
```
git status
```
- Displays the commit history for the current branch:
```
git log
```
- Shows the file differences not yet staged:
```
git diff
```
- Shows the differences between staged changes and the last commit:
```
git diff --staged
```

## Branching and Merging

- Lists all local branches:
```
git branch
```
- Lists all branches, local and remote:
```
git branch -a
```
- Switches to the specified branch:
```
git checkout [branch-name]
```
- Creates and switches to the specified branch:
```
git checkout -b [branch-name]
```
- Merges the specified branch into the current branch:
```
git merge [branch]
```

## Sharing and Updating

- Fetches changes from the remote repository and merges them into the current branch:
```
git pull [remote] [branch]
```
- Pushes the current branch to the remote repository:
```
git push [remote] [branch]
```
- Adds a new remote repository:
```
git remote add [shortname] [url]
```

## Undoing Changes

- Unstages the specified file, while preserving its contents:
```
git reset [file]
```
- Resets your index and working directory to the state of a specific commit:
```
git reset --hard [commit]
```
- Removes the specified file from the working directory and stages the deletion:
```
git rm [file]
```

## Advanced Git

- Downloads all changes from the remote repository but doesn't integrate any of these changes into your working files:
```
git fetch [remote]
```

Remember to replace `[url]`, `[file]`, `[commit message]`, `[branch-name]`, `[remote]`, and `[branch]` with actual URLs, file names, commit messages, branch names, remote names, and branch names when using these commands.

