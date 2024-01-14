-To remove a local branch, you can use the following command:
git branch -d branch_name

-If the branch has not been merged, you may need to force the deletion using -D:
git branch -D branch_name

-To remove a remote branch, you need to use the git push command with the --delete flag:
git push origin --delete branch_name
