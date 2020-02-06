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

## clone (copying) an existing rep

`git clone [url]`

## additional resources

https://github.github.com/training-kit/downloads/github-git-cheat-sheet/

## cloning a repo and pushing to a new one. (yours)

- cloning a repo actually prevents you from being able to push initially
- the code below can set your remote (the my-repo-git-url is the url on the clone or download button)
- make sure to clone with SSH (otherwise you have to type your username and password)

`git remote set-url origin <my-repo-git-url>`