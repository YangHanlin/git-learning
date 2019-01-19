## Overview

This acts as a final review for the learning of Git in the past several days.

*Hard to remember the Git commands? Get a copy of **Git cheatsheet** [here](https://services.github.com/on-demand/resources/cheatsheets/).*

*Also some shortcuts:*

- *Git cheatsheet (English) [here](https://services.github.com/on-demand/downloads/github-git-cheat-sheet/)*
- *Git cheatsheet (English, PDF) [here](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)*
- *Git cheatsheet (Chinese) [here](https://services.github.com/on-demand/downloads/zh_CN/github-git-cheat-sheet/)*

*You can also get a version in this site that is an archive of the English PDF version (Jan. 19th, 2019) [here](resources/github-git-cheat-sheet.pdf).*

## Markdown

The introduction of **Markdown** is taken from the brief introduction of Markdown in GitHub Pages, as below:

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

## Useful Git Commands

There are several useful Git commands.

### Basic Commands

`git init`: to initialize an empty Git repository,

`git clone`: to clone a repository from the server to current directory.

`git add`: add the specified contents to next commit.

`git commit`: to create a commit.

`git push`: to push commits to the server.

`git pull`: to pull (possible) changes form the server.

`git diff`: to work out the differences between versions.

`git log`: to show the log of commits.

### Branching

`git branch`: to list all branches in the current repository,

`git branch <branch>`: to locally create a new branch from its name given.

`git checkout <branch>`: to check out to the branch specified.

`git checkout -b <branch>`: to create a new branch with the name given and check out to the branch.

`git push -u origin <branch>`: to publish the specified branch to the server.

`git branch -d <branch>`: to delete a branch locally.

`git push origin –delete <branch>`: to delete a branch in the server.

### Interacting between Branches

`git merge <branch>`: merge the specified branch into the current branch.

`git rebase <branch>`: to rebase current branch onto the specified branch.

