# Git Cheat Sheet

# [Download PDF](https://github.com/CyberBoyAyush/GitCheatSheet/releases/download/PDF/GitCheatSheet.pdf)

![Image 1](https://github.com/CyberBoyAyush/GitCheatSheet/blob/master/assets/git-cheat-sheet-education-1.jpg)
![Image 1](https://github.com/CyberBoyAyush/GitCheatSheet/blob/master/assets/git-cheat-sheet-education-2.jpg)

Git is the free and open source distributed version control system that's responsible for everything GitHub
related that happens locally on your computer. This cheat sheet features the most important and commonly
used Git commands for easy reference.

#INSTALLATION & GUIS
GitHub for Windows:
https://windows.github.com

GitHub for Mac:
https://mac.github.com

For Linux and Solaris platforms, the latest release is available on
the official Git web site.
Git for All Platforms
http://git-scm.com

# SETUP
Configuring user information used across all local repositories.

## Name Config:
`git config --global user.name “your_name”`

## Email Config:
`git config --global user.email “your_email”`

# Initialize and Setup Repositories Locally
## Clone:
`git clone repo_link`

## Initialize Local Repository:
`git init`

# Stage and Commit
## Stage All Changes:
`git add .`

## Stage only selected files:
`git add [file_name]`

## Unstage File:
`git reset [file_name]`

## Commit:
`git commit -m “commit_message”`

## Check what is changed but not yet staged:
`git diff`

## Check what is staged but not yet commited:
`git diff --staged`

# Branch and Merge
## See branch list:
`git branch`

## Create Branch:
`git branch branch_name`

## Checkout Branch (Change Working Branch):
`git checkout branch_name`

## Merge Branch:
`git merge branch_name`

# Commit History and Status
## Commit Logs:
`git log`

## Commit Logs Specific Results:
`git log [number]` say `git log 5`

## Check Status:
`git status`

# Remote Origin
## Add Origin:
`git remote add origin repo_url`

## Remove Origin:
`git remote remove origin`

## Check Repo Origin:
`git remote -v`

# Pull, Push, Fetch
## Pull Changes:
`git pull`

## Push Changes to origin:
`git push origin branch_name`

## Fetch:
`git fetch`

# Contribute
Contribute to this project by sending [pull request](https://github.com/CyberBoyAyush/GitCheatSheet/pulls) and by [raising issue](https://github.com/CyberBoyAyush/GitCheatSheet/issues)

# LICENSE📋
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

* Copyright (C) 2021-2022 by CyberBoyAyush@Github, < https://github.com/CyberBoyAyush >.

Git Cheat Sheet is Free Documentation: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
