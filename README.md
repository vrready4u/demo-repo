# demo-repo
## this is a demo repo to test git concepts

# feature branch 

1. use checkout to switch between branches
$ git checkout -b <feature branch name>
-b is to for creating new branch 

2. modify readme file 
3. stage and commit changes 

4. go back to main 
git checkout main all those changes will not be visible since its made on feature branch 

 5. if we cwant we can merge these branches locally using git merge but first we can do a git diff to see what changes are made. 
 git diff feature-branch name # comapres the feature to main 
 (note: get out of the feature branch if you wanna see the diff (go to main branch and use git diff)). 
 hit 'q' to get out diff output. 

 6 hit git push 
 it will prompt  you the right command 
 $git push --set-upstream origin feature branch name
 

7 . deleting a feature branch 
git branch -d feature branch name #locally
git push origin --delete feature branch name # for deleting remotly.



8. merge conflict , created abranch test rbranch , modified index.html and changed the same line
differntly in main and test branch 
when we do git merge main, we get a merge conflict
we can use visual studio code to accept the changes and resolve the conflict manually.
then we get another commit to be made in test branch and then we commit and merge again .


9. undo a staging 
git reset or 
git reset filename 
to undo staging

10 git reset HEAD 
head is a pointer to the latest commit 

git reset HEAD~1 
one commit before the latest

git log # to view all the commits 
 git reset commit id 

 git reset --hard commit id , not jsut unstaging but completing earasing the cmmit .
 