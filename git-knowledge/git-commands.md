### delete a branch in a remote repository

```bash
git push --delete origin [branch name]
```
### discard all local changes (not committed)
'''
FOR UNSTAGED
git restore . OR git restore path/to/file/to/revert
FOR STAGED
git reset --hard
