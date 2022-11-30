# test-repo
## screenshot of the task
![image](https://user-images.githubusercontent.com/29038590/204748238-bf5bb249-f438-47df-bbfe-fadda49d6b6f.png)

## Solution for the task
1. Cloned the repo as a submodule
2. Used the `git rebase` command to add the changes in the reverse branch using `git rebase remotes/origin/feature/reverse master`. This command will rebase the changes of reverse branch to master.
3. Used the `git rebase` command again to add the changes of uppercase branch using `git rebase remotes/origin/feature/uppercase master`. This command will rebase the changes of uppercase branch to master. However, after running this command there were merge conflicts. so I had to remove the merge conflicts and continue the rebase process with command `git rebase --continue` command to continue with the rebase process.
