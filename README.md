# Demo5
experiment5
<br>
To fetch the latest changes from a remote repository and rebase your local branch onto the updated remote branch in Git, follow these steps:

1. Open your terminal or command prompt.

2. Switch to your local branch:
   $ git checkout <branch-name>

3. Fetch the latest changes from the remote repository:
   $ git fetch origin

4. Rebase your local branch onto the updated remote branch:
   $ git rebase origin/<branch-name>

5. Resolve any conflicts during the rebase:
   - Edit conflicting files, then stage them:
     $ git add <file-name>
   - Continue the rebase:
     $ git rebase --continue

6. Push the rebased changes to the remote repository (use --force cautiously):
   $ git push origin <branch-name> --force

By following these steps, you can update your local branch with the latest changes from the remote branch while maintaining a clean commit history.

