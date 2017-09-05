# Git Syntax cheat sheet

* Remove unstaged change files
```
git stash
git stash drop
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
