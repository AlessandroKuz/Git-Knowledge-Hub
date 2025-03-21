# Git-Knowledge-Hub
A simple repository an Obsidian Vault where I'll store my knowledge related to #Git and #VCS.

**IT IS NOT MEANT TO BE A COMPREHENSIVE TUTORIAL** (At least not at the moment), just a single place where most of the useful info lies for reference.

Most of the content is based off the [Pro Git Book](https://git-scm.com/book/en/v2).
## Basics
Git and more generally any VCS (Version Control System), serves the purpose to facilitate the "versioning" of code, i.e. keeping tracking of changes with time. The main difference between saving the file directly and saving changes is that it is easier to roll-back and check for differences; it also allows to have backups and get a history simply. It also helps when you have to collaborate with other people or experiment in different branches.

So the main benefits of using Git are the following:
- Keep history
- Allow collaboration
- View changes
- Experiment through branching
- Make backups
- Has working and staging areas:
	- to review your changes
	- to pick what gets updated
### Centralized vs Decentralized
- **Centralized**, the source code is hosted on a single server and changes are pushed there
- **Decentralized**, the source code is distributed to each of the collaborators machines, allowing them to work in parallel and independently (even offline)
### Repository
A #Repository or #Repo is a Database where all the changes are stored. It can be viewed as a folder with all the information about the project.
#### Local vs Remote
The cha
#### Working and staging areas
- **Working** area:
- **Staging** area:
	
- Tracked
- Untracked
## GitHub
Remote Repository that stores all of your changes in their website.
## Pull request
Request to merge a branch into another one. Once a pull request is open in can be reviewed, if approved one can accept and merge the changes.
## Setup
Once you install git onto your machine, it is recommended to configure it.
For example by adding username and email:
```shell
git config --global user.name "YourName"
git config --global user.email you@yourdomain.example.com
```
## Commands
[[Most-Common-Commands]]
[[All-Commands]]
### config
--global
user.name
user.email
### init
When you start a new project you run `git init` in your terminal, this initializes the repository and starts tracking changes.
### add
Allows you to add specific changes to the staging area.
### restore
### commit
Allows you to "save" the staged changes and associate a description or message to it.
A good practice to follow is that of  [[Conventional-Commits]], which are a standard way to format your descriptions to easily understand what type of changes were made and what was the scope.
### status
### reset
### push
When
### pull
### fetch
### merge
### log
Show you the history of all the commited changes.
### stash
### rebase
### switch
### branch
To list or switch branches
### checkout
Useful to switch to previous versions of the repository
to create new branches
### remote
to setup and check for remote repo
### diff