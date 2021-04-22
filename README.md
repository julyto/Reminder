# Reminder

## GIT
* Push branch on remote repository 
```
git checkout -b ma_branche_de_developpement
git push -u repository_distant ma_branche_de_developpement
```

* Get all changed on remote repository
```
git fetch upstream
git merge upstream/master
```
or
```
git fetch upstream
git rebase upstream/master
```

* Update a branch with modif from upstream
```
git push -f origin ma_branche_de_developpement
```
