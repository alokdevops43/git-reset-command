# Git Reset Command

A simple project created while learning the `git reset` command.

## Live link 

https://alokdevops43.github.io/git-reset-command/

## About

`git reset` is used to move the current branch to a previous commit and modify the staging area depending on the option used.

## Types of Reset

### Soft Reset

```bash
git reset --soft HEAD~1
```

Removes the commit and keeps changes staged.

### Mixed Reset (Default)

```bash
git reset HEAD~1
```

Removes the commit and unstages the changes.

### Hard Reset

```bash
git reset --hard HEAD~1
```

Removes the commit and permanently deletes the changes.

## Technologies Used

* HTML
* CSS
* JavaScript
* Git
* GitHub
