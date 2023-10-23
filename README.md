# created the repo locally
## local repository -> "remote" repository
`git add remote <name> <URL>`

# created the repo remotely
`git clone <URL>`

# create a branch locally
```Shell
git checkout <branch>
git checkout -b <new branch>
git add ...; git commit -m "..." (several times)
git push --set-upstream origin <new branch>
git pull [origin <new branch>]
```

# create a new branch remotely using the GitHub UI to create <branch>
```Shell
git fetch --all
git checkout <branch>
```