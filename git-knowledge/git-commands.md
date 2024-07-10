### delete a branch in a remote repository

```bash
git push --delete origin [branch name]
```

### discard all local changes (not committed)

````bash
- FOR UNSTAGED

git restore . OR git restore path/to/file/to/revert

- FOR STAGED
  git reset --hard

### delete branch

git branch -d(-D) [branch name]

### merge

```bash
git merge [source branch name]
````

- Cancels the merge

```bash
git merge --abort
```
