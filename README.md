# git-demo
Demo repo

## Git Commands
* git log - history
* git status
* git add
* git commit
* git push
* git clone repository-url

### Git GUI
* git gui&
* gitk& - viewing the history of the commits

### Undoing things
* git checkout -- file
* git checkout .
* git clean -xdf ----> to remove files

##### When added in the index
* git reset -- file.txt

### Reverse/Delete a commit
* git commit --amend -m "message"
* git reset HEAD^^ or (HEAD~2)

We can combine those commands to unchange things

### Git reset

* git reset --soft HEAD~1 - going back one commit and files are in the index stage - with soft file are not removed
* git reset --mixed HEAD~1 - with mixed flag, we're going back and files are in the file stage - with mixed files are not removed.
* git reset --hard HEAD~1 - going back one commit - everything is removed - be carefull with this flag

### Git Revert - revert changes after pushing to github

* git revert e46bd
* git revert "last shi1 revert" so we can revert a revert :v

### Git ignore
To specify what type files we are going to change
We have to create a file starting with a full stop, because it must be hidden, called .gitignore.

## Branching

### Create a new branch
* git checkout -b feature