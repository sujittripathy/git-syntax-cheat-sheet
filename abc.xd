# Git Syntax cheat sheet

* Remove unstaged change files
```
git stash
git stash drop
git stash pop (while popping files, this will merge the files)
git stash list (just list down all the stash list and not the file details)
git stash show (list down all the files on stash)
```

* Reset local branch changes for all files
```
git reset --hard HEAD
```
* Rename file in Git
```
git mv <old file name full path> <new file name>
```
* Undo a local file change. This will undo the local changes and replace with remote version.
```
git checkout HEAD <file_name>
```
* Delete a branch from local
```
git branch -D <local_branch_name>
```

* Display history of branches in local
```
git log --all --decorate --graph --oneline --pretty=oneline
```

* Rebasing from remote branch with local after commit of files to local branch
```
git rebase origin/master
git rebase --skip (if rebase gets stuck due to any issue, either resolve or skip)
git push origin <feature branch>
```

* Where remote is pointing to 
```
git remote -v
```
* Clone a specific branch from remote git
```
git clone -b release_branch_1704.1 https://github.wellsfargo.com/app-1CUST/CustomerConversationTool.git
```
