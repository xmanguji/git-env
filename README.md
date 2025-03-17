# How to remove last commit in git

```
 git checkout 53a40b0ad343701c1885c252aa3a268471e47e28
 git branch    
 git branch -D last-publish
 git checkout -b last-publish
 git push
 git push --set-upstream origin last-publish
 git checkout main
 git pull
 git branch
 git checkout chris`
```
