Directory Management
Create a new directory
mkdir git-for-devops

List directory contents
ls

Change directory
cd git-for-devops

Print current directory path
pwd

Clear terminal screen
clear

File Management
Create or edit a file
vim hello-dosto.txt

View file content
cat hello-dosto.txt

Remove a file
rm hello-dosto.txt

Create an empty file
touch hello-dosto.txt

Create multiple empty files
touch nibba.txt nibbi.txt

Git Initialization
Initialize a new Git repository
git init
Git Configuration
Set global username
git config --global user.name "sr-palatasingh"

Set global email
git config --global user.email "srpalatasingh@gmail.com"

Git Status
Check repository status
git status
Adding Files to Staging
Add a file to the staging area
git add nibbi.txt

Unstage a file
git rm --cached nibba.txt

Committing Changes
Commit changes with a message
git commit -m "Commit message"
Viewing Commit History
View detailed commit log
git log

View commit log in one-line format
git log --oneline

Branch Management
List branches
git branch

Create and switch to a new branch
git checkout -b dev

Switch to an existing branch
git checkout master

Switch between branches (alternative)
git switch dev

Editing Files
Edit a file
vim nibbi.txt
File and Branch Operations
Add a new file and commit it
touch nibbu.txt
git add nibbu.txt
git commit -m "added nibbu"
Branch Creation from Existing Branch
Create a new branch from the current branch
git checkout -b from-dev
Command History
View command history
history
