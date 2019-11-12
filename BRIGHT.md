How to update this repo

Add the offical repo as a remote
`git remote add SolidStateGroup git@github.com:SolidStateGroup/bullet-train-frontend.git`
Your remotes should now look like this:
```
git remote -v 
SolidStateGroup	git@github.com:SolidStateGroup/bullet-train-frontend.git (fetch)
SolidStateGroup	git@github.com:SolidStateGroup/bullet-train-frontend.git (push)
origin	git@github.com:brightinteractive/bullet-train-frontend.git (fetch)
origin	git@github.com:brightinteractive/bullet-train-frontend.git (push)
```

Fetch the latest changes
`git fetch SolidStateGroup`
remote: Counting objects: 100% (727/727), done.

Rebase our tweaks on top of the latest changes, fixing any conflicts
`git rebase SolidStateGroup/master`

Push your changes
`git push -f`

