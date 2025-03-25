# Git Commands Guide

## Repository Management

- `git init` - Initialize a new Git repository
- `git clone <repo-url>` - Clone a repository from a URL

## Basic Commands

- `git status` - Show the status of changes
- `git add <file-name>` - Add changes to the staging area
- `git commit -m "message/title"` - Commit changes with a descriptive message
- `git log` - View commit history

## Branching

- `git branch` - List branches
- `git branch -M <branch-name>` - Create and rename a new branch
- `git checkout <branch-name>` - Switch to a specific branch  
- `git merge <branch-name>` - Merge changes from a branch
- `git branch -d <branch-name>` - Delete a branch

## Remote Repositories

- `git remote` - List remote repositories
- `git remote add <name> <url>` - Add a remote repository
- `git push <remote> <branch>` - Push changes to a remote repository
- `git pull <remote> <branch>` - Pull changes from a remote repository

## Undoing Changes

- `git pull` - Fetch and merge changes from the remote repository
- `git fetch` - Fetch changes without merging
- `git reset --hard HEAD` - Discard all local changes
- `git revert <commit-hash>` - Revert changes in a specific commit

## Notes

This guide provides a quick reference to essential Git commands for repository management, branching, remote operations, and undoing changes.

