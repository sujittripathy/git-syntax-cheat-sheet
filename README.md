# Git Syntax cheat sheet

* Remove unstaged change files
```
git stash
git stash drop
git stash pop (while popping files, this will merge the files)
git stash list (listing all the files on stack)
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
