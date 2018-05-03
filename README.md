# practise
For learning git
trying out branching, merging etc.

1. Create an new branch localy:
   git checkout -b iss53
2. Create a hotfix in between and merge to master
    git checkout -b hotfix
 edit files and commit
 Merge with master
   git checkout master
   git merge hotfix
 Remove branch
   git branch -d hotfix
3. Switch back to iss53 branch
   git checkout iss53


