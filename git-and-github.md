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

## Repositories (Repos)

* Collection of files you're told Git to pay attention to
* Usually one project = one repository
* Large projects may have multiple repositories
* Can live on GitHub and/or on your computer


### Clone a repository

Get URL for repository from GitHub
In terminal, go to the directory where you want to put the repository on your machine.
Use command `git clone <link from github>` to clone the repo
The repo is now a directory on your machine. It will show `[master]` in the terminal.

