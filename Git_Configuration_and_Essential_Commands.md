# Git Configuration & Essential Commands

A quick reference guide for configuring Git and using common commands.

## Check Git Version

``` bash
git --version
```

## View Configuration

``` bash
git config --list
```

## Get Global Username

``` bash
git config --global user.name
```

## Get Global Email

``` bash
git config --global user.email
```

## Set Global Username

``` bash
git config --global user.name "Your Name"
```

## Set Global Email

``` bash
git config --global user.email "you@example.com"
```

## Remove Incorrect Username

``` bash
git config --global --unset user.name
```

## Remove Incorrect Email

``` bash
git config --global --unset user.email
```

## Verify Settings

``` bash
git config --global user.name
git config --global user.email
```

## Initialize Repository

``` bash
git init
```

## Clone Repository

``` bash
git clone https://github.com/username/repository.git
```

## Check Status

``` bash
git status
```

## Stage Changes

``` bash
git add .
```

## Stage Specific File

``` bash
git add filename
```

## Commit

``` bash
git commit -m "Your commit message"
```

## View History

``` bash
git log --oneline
```

## Branches

``` bash
git branch
git switch branch-name
git switch -c new-branch
```

## Push

``` bash
git push origin main
```

## Pull

``` bash
git pull origin main
```

## Fetch

``` bash
git fetch
```

## Remotes

``` bash
git remote -v
git remote add origin https://github.com/username/repository.git
git remote set-url origin https://github.com/username/repository.git
```

## Restore

``` bash
git restore filename
git restore --staged filename
```

## Delete Branch

``` bash
git branch -d branch-name
git push origin --delete branch-name
```

## Diff

``` bash
git diff
git diff --staged
```

## Stash

``` bash
git stash
git stash pop
git stash list
```

## Typical Workflow

``` bash
git status
git add .
git commit -m "Describe your changes"
git push origin main
```

## Most Used Commands

  Command                     Purpose
  --------------------------- -----------------------
  `git --version`             Check Git version
  `git config --list`         View configuration
  `git status`                Check status
  `git add .`                 Stage changes
  `git commit -m "message"`   Commit
  `git push origin main`      Push
  `git pull origin main`      Pull
  `git fetch`                 Fetch
  `git branch`                List branches
  `git switch`                Switch branch
  `git log --oneline`         Commit history
  `git diff`                  Show changes
  `git stash`                 Save work temporarily
  `git remote -v`             View remotes
