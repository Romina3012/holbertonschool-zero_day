#  Key commands of git
- Push

The git *push command is used to upload local repository content to a remote repository*. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.
- Pull

The git *pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content*. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows.
- Add

The git *add command adds a change in the working directory to the staging area*. It tells Git that you want to include updates to a particular file in the next commit. However, git add doesn't really affect the repository in any significant way—changes are not actually recorded until you run git commit .
- Commit

The *commit command is used to save your changes to the local repository*. Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command. This means that a file won't be automatically included in the next commit just because it was changed.
- Branch

The git *branch command lets you create, list, rename, and delete branches*. It doesn't let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands.
- Checkout

The git *checkout command lets you navigate between the branches created by git branch*. Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

- Status 

The *status command shows the status of files in our repository if they have been added or modified accordingly to our previous branch status*.
