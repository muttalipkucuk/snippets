# .gitignore not working when files are already committed

1. Commit everything (also `.gitignore` file) so you have nothing to commit
2. Remove everything from your repo by: 
```
git rm -r --cached .
```
3. Re-commit everything again by:
```
git add .
git commit -m ".gitignore fix"
```
