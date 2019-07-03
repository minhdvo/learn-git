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
