\# Git Team Sync Workflow



\## 1. Why was the push rejected?



The push was rejected because the remote repository had new commits that were not yet in the local repository. Git prevents the local branch from overwriting changes that already exist on the remote.



\## 2. Merge vs. Rebase



A merge combines two different lines of development and creates a merge commit.



A rebase moves the local commits so they are applied on top of the updated remote branch. This creates a more linear history.



\## 3. How can we avoid rejected pushes?



Before starting work or pushing changes, fetch the latest changes from the remote repository and check whether the local branch is up to date.



\## 4. Team Workflow



1\. Fetch changes from the remote repository.

2\. Check the current branch and status.

3\. Make changes to the files.

4\. Run the tests.

5\. Commit changes using the required commit-message format.

6\. Fetch again before pushing when working with shared branches.

7\. Resolve conflicts if Git reports any.

8\. Push the completed changes to the remote repository.

9\. Keep the `main` branch synchronized with the completed feature work.



