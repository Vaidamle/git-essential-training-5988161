# Example: Git Essential Training

This file demonstrates a minimal example and common Git commands for quick reference.

## Location
C:/Vaibhav/Learning/git_essential_training/git-essential-training-5988161/example.md

## Purpose
Show a concise example and a few commands to get started with a repository.

## Quick commands
```bash
# initialize a new repo
git init

# clone an existing repo
git clone <url>

# check status and staged changes
git status
git add <file>
git commit -m "Describe changes"

# view history
git log --oneline --graph --decorate

# branches and merging
git branch           # list branches
git checkout -b feat  # create and switch to branch
git merge feat

# sync with remote
git push origin main
git pull
```

## Notes
- Keep commits small and focused.
- Use clear commit messages.
- Create branches for features or fixes.
- Run `git status` often to understand repository state.