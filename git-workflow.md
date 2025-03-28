Finish forking a repository

git remote add upstream https://... (add the url to original repo, not the fork)

git fetch upstream

git branch --set-upstream-to upstream/main

Syncing a forked repository:
1. Pull changes from upstream then push to origin

git pull upstream main --ff-only

CHANGE BRANCHES!g

git push origin main pushes changes to my version of the fork (origin)

creating a pull request:

Use the usethis package:
a. On branch, add and commit changes from terminal
b. still on branch, switch to console and use pr_push() to open pull request on remote


After pull request is made, switch to main branch. Merge branch to main, then delete branch. Then push project origin main 
