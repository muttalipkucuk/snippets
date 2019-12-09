# .gitignore not working when files are already committed

1. Commit everything (also `.gitignore` file) so nothing is left to commit
2. Remove everything from the remote repo by: 
```
git rm -r --cached .
```
3. Re-commit everything again by:
```
git add .
git commit -m ".gitignore fix"
```
