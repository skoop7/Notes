# GIT

GIT is a free open source version control tool that developers install locally
on their personal computers.while GitHub is a pay-for-use online service build to run Git in the cloud.

you can see the URL that local Git repository was originally cloned from

```
git remote show origin
```

to add the data/file into staging area use

```
git add file.txt /

git add .
```

to commit the changes from staging area

```
git commit -m "first commit"
```

then we can rename the branch using -M

```
git branch -M main
```

to connect to remote repository

```
git remote add origin "url"
```

to push the changes to connected remote repository

```
git push -u origin main
```

to get your current branch

```
git branch
```

to navigate between branches

```
git checkout branchname
```

to create a branch

```
git checkout -b branchname
```

to delete a branch

```
git branch -d branchname
```

to compare between branches

```
git diff branchname
```

to merge diffrent branches

```
git merge branchname
```

to undo one commit

```
git reset HEAD-1
```

to undo multiple commits

```
git reset <commit-hash>
```
