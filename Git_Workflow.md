# What is Git after all?

Distributed Version Control System - All Repositories are equal even your local one!

* https://www.atlassian.com/git/tutorials/what-is-git
* https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud

From https://medium.com/@eduoshaun/difference-between-git-and-github-807f1a57d438

![Local file control](img/local_version_control.png)

![Centralized Version Control](img/central_version_control.png)

![Distributed Version Control](img/distributed_version_control.png)


## Install Git locally
* https://git-scm.com/downloads
* https://www.atlassian.com/git/tutorials/install-git

## First Time Setup
* https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
* https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-config

## Start using the repo run in terminal: 
*git clone https://github.com/ValRCS/RCS_Web_Development_07_2019.git*
* clones whole repo in the current working directory from which you run git clone

* git log shows revision history with SHA1 hash value for each revision

## Update automagically original repo: *git pull* from the same directory
* git pull is like two commands into one
* git fetch + git merge pulls changes from default origin(this repo) into your local repo and merges them 

## Edit/Move Files in local clone from command line terminal
* git status for status
* git add . from project root to stage changes
* git status to make sure
* git commmit -m "My helpful commit message" to commmit **locally**
* git push origin to push back to master repo (Github will ask to login and pw if no SSH set)

## If you want to work on specific revision
* git clone URL 
* cd to Projectdirectory
* git reset --hard SHA1 where SHA1 is SHA1 of the revision you want

* git pull to get back to HEAD revision





### Various workflows: https://www.atlassian.com/git/tutorials/comparing-workflows

### Git Cheatsheet

* https://www.atlassian.com/dam/jcr:8132028b-024f-4b6b-953e-e68fcce0c5fa/atlassian-git-cheatsheet.pdf

### Git Basics in 10 minutes
* https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/
* https://www.freecodecamp.org/news/git-the-laymans-guide-to-understanding-the-core-concepts/

### Git Graphical Clients
* https://git-scm.com/downloads/guis

## Git support in Visual Studio Code
* https://code.visualstudio.com/docs/editor/versioncontrol

## Git Bash commands
* https://www.atlassian.com/git/tutorials/git-bash

### How to Git Init locally then push later to Remote (such as Github)

* https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line
