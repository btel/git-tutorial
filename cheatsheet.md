# Git for starters

## Main commands

`git init`  -  initalize new repository (done only once per repository)

`git add FILENAME` - stage (i.e. mark for committing) a new file (or a new change) to git repository

`git status` - get information about changed and staged files

`git commit -m "SHORT MESSAGE"` - save all changes in your local git repository

`git log` - show the history of changes with commit hashes

`git diff` - compare your local working directory to last committed version

`git diff HASH` - compare your local working directory to commit HASH

`git diff HASH_1 HASH_2` - compare commits HASH_1 and HASH_2

`git diff --color-words` - compare files with single word resolution

`git remote add origin URL` - link your local repository to a remote repository at address URL

`git push -u origin master` - push your code (with history)
to remote repository
`git pull`  - pull code and its history from remote repository

## Glossary

**git** 1) *British slang*: a fooloish or contemptible person; 2)  *Computing*: open source program for tracking changes in text files.

**repository**
   folder with one or more files that are tracked jointly by the git.

**remote repository** - repository that is hosted on a server. You can synchronise between your local and remote repository using "push" and "pull" commands.

**working directory** - all files in your project folder

**commit** - a commit or "revision" is an indivdual change to a project including one or more files that it's saved in the history of your repository.

**commit hash** - unique hexidecimal ID associated with each commit

**origin** - default remote repository to synchronise your local repository with

**stagging area** - all files and changes that are selected (using `git add`) for the next commit

**branch** - alternative versions of your respository that can co-exist and be developed indepedently. Branches can be compared, merged or discarded at any time.

**master** - main version (branch) of your repository
