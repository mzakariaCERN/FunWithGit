# FunWithGit
Useful Commands and hacks for using Git

# Resources
A git workflow model
https://nvie.com/posts/a-successful-git-branching-model/

#Useful git commands
```
 git merge --no-ff myfeature
```
The --no-ff flag causes the merge to always create a new commit object, even if the merge could be performed with a fast-forward. This avoids losing information about the historical existence of a feature branch and groups together all commits that together added the feature. see 
https://nvie.com/posts/a-successful-git-branching-model/ for more details

```
git fetch origin
git reset --hard origin/master
```

This happens in case you don't like what you did with your own version and want to set your branch to exactly match the remote branch. [see](https://stackoverflow.com/a/1628334/4656963)
