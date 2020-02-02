# cheatsheet github commands

## keywords to know

- locally: existing on your computer
- repository: a folder where git watches your file changes
  - added files
  - deleted files
  - modified files

## start a repository locally (having git watch your files and watch changes)

`git init`

## add to an existing repository locally

`git add .`
or
`git add <fileOrDirectoryName>`

`IE: git add foo.txt`

## commit a change to a repository (giving a commit of file changes to a repository)

`git commit -m "my message"`

## push to a repository (assuming its connected)

`git push origin <branchName (default is master)>`
