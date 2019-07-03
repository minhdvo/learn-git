## Install Git
- GitHub for Windows: htps://windows.github.com
- Git for All Platforms: htp://git-scm.com

## CONFIGURE TOOLING
Configure user information for all local repositories

$ git config --global user.name "[name]" <br>
Sets the name you want atached to your commit transactions

$ git config --global user.email "[email address]" <br>
Sets the email you want atached to your commit transactions

$ git config --global color.ui auto <br>
Enables helpful colorization of command line output

## CREATE REPOSITORIES
Start a new repository or obtain one from an existing URL

$ git init [project-name] <br>
Creates a new local repository with the specified name

$ git clone [url] <br>
Downloads a project and its entire version history

## MAKE CHANGES
Review edits and craf a commit transaction

$ git status <br>
Lists all new or modified files to be commited

$ git add [file] <br>
Snapshots the file in preparation for versioning

$ git reset [file] <br>
Unstages the file, but preserve its contents

$ git diff <br>
Shows file differences not yet staged

$ git diff --staged <br>
Shows file differences between staging and the last file version

$ git commit -m "[descriptive message]" <br>
Records file snapshots permanently in version history

## FILE
$ git rm [file] <br>
Deletes the file from the working directory and stages the deletion

$ git rm --cached [file] <br>
Removes the file from version control but preserves the file locally

$ git mv [file-original] [file-renamed] <br>
Changes the file name and prepares it for commit

## HISTORY
Browse and inspect the evolution of project files

$ git log <br>
Lists version history for the current branch

$ git log --follow [file] <br>
Lists version history for a file, including renames

$ git diff [first-branch]...[second-branch] <br>
Shows content differences between two branches

$ git show [commit] <br>
Outputs metadata and content changes of the specified commit

## REDO
Erase mistakes and craf replacement history

$ git reset [commit] <br>
Undoes all commits afer [commit], preserving changes locally

$ git reset --hard [commit] <br>
Discards all history and changes back to the specified commit

## SYNCHRONIZE CHANGES
Register a repository bookmark and exchange version history

$ git fetch [bookmark] <br>
Downloads all history from the repository bookmark

$ git merge [bookmark]/[branch] <br>
Combines bookmark’s branch into current local branch

$ git push [alias] [branch] <br>
Uploads all local branch commits to GitHub

$ git pull <br>
Downloads bookmark history and incorporates changes
