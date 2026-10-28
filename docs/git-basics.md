# Git Basics

## Introduction

Git is a distributed version control system used to track changes in files and coordinate work among developers.

## Important Git Commands

| Command | Purpose |
|---|---|
| `git init` | Initialize a Git repository |
| `git status` | Check the working tree status |
| `git add <file>` | Stage changes |
| `git commit -m "message"` | Record staged changes |
| `git log --oneline` | View a compact commit history |
| `git branch` | List branches |
| `git switch -c <branch>` | Create and switch to a branch |
| `git merge <branch>` | Merge a branch into the current branch |
| `git stash` | Temporarily save eligible uncommitted changes |
| `git tag` | List or manage tags |
| `git diff` | Inspect unstaged changes |

## Git Workflow

1. Modify project files.
2. Inspect changes using `git status` and `git diff`.
3. Stage the intended changes using `git add`.
4. Create a commit using `git commit`.
5. Push commits to a remote repository when ready.

## Best Practices

- Write meaningful commit messages.
- Make small, focused commits.
- Review changes before staging.
- Never commit passwords, tokens, or private keys.
- Use branches to isolate new work.

## Branching Strategy

This project uses separate branches to organize development work.

- `main`: Stable project version.
- `dev`: Integration and development work.
- `feature/*`: Individual changes and improvements.

Feature branches should be reviewed before merging into the target branch.
