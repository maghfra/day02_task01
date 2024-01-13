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

=========================================================================
# How to List Tags
# List all tags
git tag
Thisi commands will display the list of tags in your local repository.

Fetch tags from the remote repository
git fetch --tags
List all tags
git tag -l

=======================================================
# How to Delete a Tag Locally and Remotely
Delete Tag Locally:
git tag -d tagName
Delete a remote tag
git push --delete origin tagName

====================================================
![readme](https://github.com/maghfra/day02_task01/assets/156420828/b62dc712-e6f0-41e9-a639-ad0eef2c7e73)

===================================================


