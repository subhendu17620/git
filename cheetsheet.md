## Install Git

GitHub for Windows https://windows.github.com

GitHub for Mac https://mac.github.com

## configure tools
### configure user info for all local repository

`git config --global user.name "[name]"`
>sets the name you want attached to your commit transactions

`git config --global user.email "[email address]"`
>Sets the email you want attached to your commit transactions

`git config --global color.ui auto`
>Enables helpful colorization of command line output


## create repositories
### Start a new repository or obtain one from an existing URL

`git init [project-name]`
>Creates a new local repository with the specified name

`git clone [url]`
>Downloads a project and its entire version history


## make changes
### Review edits and craft a commit transaction

`git status`
> Lists all new or modified files to be committed

`git add [file]`
>Snapshots the file in preparation for versioning

`git reset [file]`
>Unstages the file, but preserve its contents

`git diff`
>Shows file differences not yet staged

`git diff --staged`
>Shows file differences between staging and the last file version

`git commit -m "[descriptive message]"`
>Records file snapshots permanently in version history


## GROUP CHANGES
### Name a series of commits and combine completed efforts

`git branch`
>Lists all local branches in the current repository

`git branch [branch-name]`
>Creates a new branch

`git checkout [branch-name]`
>Switches to the specified branch and updates the working directory

`git merge [branch]`
>Combines the specified branch’s history into the current branch

`git branch -d [branch-name]`
>Deletes the specified branch


## review history
### Browse and inspect the evolution of project files
`git log`
>Lists version history for the current branch

`git log --follow [file]`
>Lists version history for a file, including renames

`git diff [first-branch]...[second-branch]`
>Shows content differences between two branches

`git show [commit]`
>Outputs metadata and content changes of the specified

## redo commits
### Erase mistakes and craft replacement history

`git reset [commit]`
>Undoes all commits after [commit], preserving changes locally

`git reset --hard [commit]`
>Discards all history and changes back to the specified commit

## syncronize changes
### Register a repository bookmark and exchange version history

`git fetch [bookmark]`
>Downloads all history from the repository bookmark

`git merge [bookmark]/[branch]`
>Combines bookmark’s branch into current local branch

`git push [alias] [branch]`
>Uploads all local branch commits to GitHub

`git pull`
>Downloads bookmark history and incorporates changes
