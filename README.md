# Git Commands

**Get remote urls**
> git remote -v

**Get origin urls**
> git config --get remote.origin.url

**Change origin urls**
> git remote set-url origin [remote url]

**Fetch from upstream**
> git fetch upstream

**Merge the changes from upstream/master into your local master branch**
> git pull upstream master

**Compare fork file with main stream in GitHub**
> https://github.com/[YOUR_USERNAME]/Code-Ground/compare/master...[MAIN_STREAM_USERNAME]:master

**Create the branch on your local machine and switch in this branch :**
> git checkout -b [name_of_your_new_branch]

**Create a new branch:**
> git branch [name_of_your_new_branch]

**Push the branch on github :**
> git push origin [name_of_your_new_branch]

**You can see all the branches created by using :**
> git branch -a

**Checkout/ Switch the branch you want to use.**
> git checkout [feature_branch]

**Update your branch when the original branch from official repository has been updated :**
> git fetch [name_of_your_remote]

**Then you need to apply to merge changes if your branch is derivated from develop you need to do :**
> git merge [name_of_your_remote]

**Delete a branch on your local filesystem :**
> git branch -d [name_of_your_new_branch]

**To force the deletion of local branch on your filesystem :**
> git branch -D [name_of_your_new_branch]

**Delete the branch on github :**
> git push -d origin [name_of_your_new_branch]








