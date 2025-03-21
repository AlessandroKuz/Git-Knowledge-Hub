# Most-Common-Commands
## Documentation
To check the manual for specific command the are two main ways:
- `man git-$COMMAND`, for example `man git-log`
- `git help $COMMAND`, for example man `git help log`
If you want a more concise description of the command you could also use `tldr` if you have it installed, to use it: `tldr git-$COMMAND`.
## Project initialization
to start a new project:
- `git init` starts a new repository in the current folder; this command will also create a `.git` directory, containing all data related to the repo.
if linking to a remote repository
- `git remote`
	- `git remote -v` show associated remote repo
	- `git remote ...
## Working and staging areas
- `git add`
- `git restore`
- `git commit`
- `git diff`
	- the `--staged` or `--cached` flags only show the differences for staged files
- `git status`
## History
- `git log`
- `git checkout #COMMIT-HASH`
## Branches
- `git branch`
- `git switch`
- `git merge`
## Remote repository
- `git remote`
- `git push`
- `git pull`
- `git fetch`