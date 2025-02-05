Git Commands Cheat Sheet

Directory and File Operations

Create a new directory

mkdir git-for-devops

List files in the directory

ls

Change directory

cd git-for-devops/

Print working directory
pwd

Clear the terminal screen

clear

Create a new file using vim

vim hello-dosto.txt

Create multiple files

touch nibba.txt nibbi.txt

Remove a file

rm hello-dosto.txt

Git Initialization and Configuration

Initialize a Git repository

git init

Check repository status

git status

Set global username

git config --global user.name "abdullah"

Set global email

git config --global user.email "skabdullah@gmail.com"

Staging and Committing Changes

Add a file to staging area

git add nibbi.txt

Add multiple files

git add nibba.txt

Remove file from staging area

git rm --cached nibba.txt

Commit changes with a message

git commit -m "adding nibba nibbi"

Restore a deleted file

git restore nibbi.txt

Commit additional changes

git commit -m "added new changes to nibbi"

Branching and Switching Branches

List all branches

git branch

Create a new branch

git checkout -b Dev

Switch to a branch

git checkout master

Create and switch to a new branch from another branch

git checkout -b from-master
git checkout -b from-dev

Viewing Logs and Status

View commit history

git log

View commit history in one line

git log --oneline

Additional Commands

Clear the screen

clear

Check current status

git status

 
