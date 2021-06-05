# valuable-team-git-commands

- `git checkout -b name-of-branch` : this will **create** a new branch off of what you checked out from...at this point, most often that will be creating a branch off of `main`
-  `git checkout name-of-branch` : this will **move** you over to this branch ... with `git checkout main` to get back to the main branch 
- `git pull`: this will bring down locally all code updates (and branches!) that exist in your remote team repository 
- `git merge main` : if you are on your particular branch, and let's say updates have been merged into `main` ... you can do a `git pull` on `main` and then checkout to your branch with `git checkout your-branch-name` and do `git merge main`... this will provide you with the most up to date code base as you continue working on your branch


## commands to be careful of
These commands do not need to be used...if you find yourself in a google search for advice and these are recommended, then something is wrong with your initial workflow. Be careful of things like `git rebase` , `git reflog`, `git fetch` ... more to come 


## merge conflicts
Merge conflicts will occur and that is ok! These happen when team members are working closely in the same part of the code base... this will happen less often as the code base gets bigger and teammates move into different files and different features... early on, it is wise to "mob" the initial database until things get built enough you all feel comfortable branching off onto your own features. To fix most conflicts, we can resolve these locally in your editor. For starters, we will handle these on a case by case basis and walk teams thru them when they happen. 
