# cheatsheet github commands

## keywords to know

- locally: existing on your computer
- repository: a folder where git watches your file changes (aka repo)
  - added files
  - deleted files
  - modified files

## start a repository locally (having git watch your files and watch changes)

`git init`

## link a github repo (repository) url below is the url that ends in .git on a newly created repo on github

`git remote add origin [url]`

## add to an existing repo locally

`git add .`
or
`git add <fileOrDirectoryName>`

`IE: git add foo.txt`

## commit a change to a repository (giving a commit of file changes to a repository)

`git commit -m "my message"`

## push to a github repository (assuming its connected with remote add origin above)

`git push origin master`

## additional resources

https://github.github.com/training-kit/downloads/github-git-cheat-sheet/
