# How to Remove Branches Locally and Remotely

# To remove branches locally:

git branch -d <branch-name>
If the branch contains unmerged changes, though, Git will refuse to delete it. 
If you’re sure you want to do it, you’ll have to force the deletion by replacing the -d parameter with an uppercase D:
git branch -D <branch-name>

# Delete the 'dev' branch
git branch -d dev


# To remove branches remotely:

To delete remote branches, run git push with the -d flag, which will cause the branch to be removed if you have access to do so.
git push origin -d <branch_name>

# Delete the 'test' branch on the remote repository
git push origin -d test

