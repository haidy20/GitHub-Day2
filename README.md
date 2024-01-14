-To remove a local branch, you can use the following command:
git branch -d branch_name

-If the branch has not been merged, you may need to force the deletion using -D:
git branch -D branch_name

-To remove a remote branch, you need to use the git push command with the --delete flag:
git push origin --delete branch_name

-how to list tags:
git tag

-how to delete tag locally and remotely:
local: git tag -d <tag_name>
remote: git push origin :refs/tags/<tag_name>

![download](https://github.com/haidy20/GitHub_Day2/assets/82911328/87fc5279-3bdf-4199-a1fc-279d790effe9)
