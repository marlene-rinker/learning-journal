# Notes about Git and GitHub

## Git

Git is software that runs on your computer and keeps track of your file system.

* DVCS - decentralized version control system
* Multiple developers work on the same code.
* Git keeps a history of your changes.
* Keep all your files in one repository.
* Commits represent each successive version of a file or files.
* Commits are the Git equivalent of Save As.
* Commits are snapshots in time.
* Each commit has a label.
* HEAD = the label meaning "You are here"
* messages - explain why you made the changes

## GitHub

GitHub is in the cloud, not on your machine.

* Central location
* Uses Git to manage your team's work

    * Version tracking
    * Reviewing changes
    * Keep changes separate until you want to add them
* Where you store your code

## Git and GitHub

Git (version control) + GitHub (online code storage)

* multiple people working on the same files without messing each other up

### Repositories (Repos)

* Collection of files you're told Git to pay attention to
* Usually one project = one repository
* Large projects may have multiple repositories
* Can live on GitHub and/or on your computer


### Clone a repository

1. Get URL for repository from GitHub
1. In terminal, go to the directory where you want to put the repository on your machine.
1. Use command `git clone <link from github>` to clone the repo.

1. The repo is now a directory on your machine. It will show `[master]` in the terminal.

`git remote -v` will get the URL of the GitHub repo (origin)

### Commands

gitflow: a-c-p = Add, Commit, Push (this is the workflow)

`git status` - gets the status of the files

`code .` - opens all files in the directory in VS Code

`code <file name>` - opens a single file (this isn't common - usually open all files)

`touch <file name>` - add a file through Terminal

`git add <file name>` - add a file 

`git add <file name> <file name>`- add multiple files

`git add .` - add all new files

When you add, Git knows about the files and can track them now. They show up as green in the Terminal.

`git commit -m 'message here'` - how to commit the files after you add them

`git push origin master` - how to push the files to the master on GitHub

`git fetch` - gets files but doesn't merge changes

`git diff origin/master` - see the difference between what's fetched and what's on our local machine

Probably won't use `git fetch` very often

`git pull origin master` - get updates (pull = fetch and merge)

## VS Code Notes

A circle in the tab instead of x means you have unsaved changes.

You have the ability to see your changes without a-c-p.

## Other

If you want to link a stylesheet to a page, do it in the head of the HTML. (This was done in an html file in the demo.)

---
[Home page](https://marlene-rinker.github.io/learning-journal/)

