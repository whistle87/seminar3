# Instruction for using sistem comtrol version

![Git emblem](picture.jpg)

## What is git

Git programm is 
A programm for commiting

## Inicialization of repository

For initialisation new repository  is needed to print in termibnat command

    git init

## Change of repository status
For checking status print commnd

    git status

## Adding changing in index

For adding changing in index for next commit you need to print a comand:    

    git add <filename>

## Record changing to commit

For record changing to commit print:

    git commit

 ## Record changing to commit with comment

 For recording changing to commit with comments with one command print:

    git commit -m "some comment"
    
## Adding changes in index and recording to commit at the same time

For adding changes in index and recording to commit together print

    git commit -a

## Adding changes in index and recording to commit with message at the same time

For adding changes in index and recording to commit with message together print

    git commit -am "message"

## Viewing a list of commiting

To look at commit log print

    git log

## Viewing a list of abbreviated commit data

To look a log of abbreviated commit data (just in one line) print

    git log --oneline

## Viewing a full list of commiting

To look at log of all commit print

    git log --all

## Viewing a full list of abbreviated commit data

To look a full log of abbreviated commit data (just in one line) print

    git log --oneline --all

## Viewing changes between file and the last commit

To look changes between file which have not yet been added to index and the last commit print

    git diff

## Switch to a commit

To switch to a needed commit print

    git checkout <hash>

## Branching

Branches in git is needed for working on different versions of original code. It gives an opportynity to work on new functions without worries about release version.

To show information about branches use:

    git branch

Green branch with * indicates on which branch are you now.

### New branch creating

For creating new branch print

    git branch branch_name 
    
For deleting branch print 

    git branch -d branch_name

### Switching between branches

For switchng between branche print

    git checkout branch_name

For creating new branch and switching on it at once print

    git checkout -b branch_name

If the branch with this name already exists this command returns an error.

### Merging

Command \<git merge> allows to merge two branches. Info from branch_name will be addet to brach from which command was called
Merging joins two or more developing histories together.

For merging changes from one branch to another print

    git merge branch_name

If merging will be done without conflict commit wil be done automatically with short message. 

### Merging conflict

If information in merging files in the same line are different merging conflict occurs.

To solve merging conflict select one of suggested options:

* Accept incoming
* Accept current
* Accept both
