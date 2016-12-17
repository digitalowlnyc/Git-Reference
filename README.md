# About  [GIT Reference]
Git tips, tricks, config samples

# How do I ...

### Commit an empty directory?
Add a `.gitignore` file with this content in the directory:
```
# Ignore everything in this directory
*
# Except this file
!.gitignore
```
Reference: http://stackoverflow.com/questions/115983/how-can-i-add-an-empty-directory-to-a-git-repository
