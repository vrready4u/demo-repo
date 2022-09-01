# demo-repo
## this is a demo repo to test git concepts

# feature branch 

1. use checkout to switch between branches
git checkout -b <feature branch name>
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
 git push --set-upstream origin feature branch name
 

