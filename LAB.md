# lab exercise
go to https://github.com/CWMe/GitGud2.git and click the fork button in the top right

clone your new forked repo
```
git clone YOUR_FORKED_REPO_URL_HERE
cd GitGud2
```

Or add the new remote
```
git remote add fork newgiturl
```

create a feature branch from master
```
git checkout -b feature-a master
```

make a change to the README.md file and commit it prepare a file for a commit
```
git add README.md
```

make the commit, a snapshot of your project is created 
```
git commit -m "updated readme"
```

# push feature branch
```
git push origin feature-a
```

# submit pull request
go to https://github.com/CWMe/GitGud2/compare and setup a new pull request from your `feature-a` branch to `master`

