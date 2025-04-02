## Git Hidden Folder

There is a hidden folder called `.git`which tells you that our project is a git repo.

If we wanted to create a git repo in a new projet we create the fikder and then initialize that repo using `git init`

``` 
mkdir /workspaces/tmp/newproject
cd /workspaces/tmp/newproject
git init
touch Readme.md
code Readme.md
# makes changes to readme.file
git commit -a -m "add readme file"
```

## Cloning

We can clone three ways: HTTPS, SSH, GitHub CLI

Since we are using GitHub Codespaces we'll create a temporary directory in our workspace

``` 
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS 

```sh
git clone https://github.com/rafaelguerrae/GitHub-Examples.git
```

## Commits

## Branches


## Remotes 

## Stashing

## Merging