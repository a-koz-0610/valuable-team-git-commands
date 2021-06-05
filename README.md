# valuable-team-git-commands

- `git checkout -b name-of-branch` : this will **create** a new branch off of what you checked out from...at this point, most often that will be creating a branch off of `main`
-  `git checkout name-of-branch` : this will **move** you over to this branch ... with `git checkout main` to get back to the main branch 
- `git pull`: this will bring down locally all code updates (and branches!) that exist in your remote team repository 
- `git merge main` : if you are on your particular branch, and let's say updates have been merged into `main` ... you can do a `git pull` on `main` and then checkout to your branch, and do `git merge main`... this will provide you with the most up to date code base as you continue working on your branch
