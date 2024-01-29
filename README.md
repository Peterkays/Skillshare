 ###50 commonly used Git commands and their usage:
1. **Initialize a Repository:**
   - `git init`: Initialize a new Git repository.

2. **Clone a Repository:**
   - `git clone [repository_url]`: Clone a repository into a new directory.

3. **Add Changes to Staging:**
   - `git add [file]`: Add changes in a file to the staging area.
   - `git add .`: Add all changes to the staging area.

4. **Commit Changes:**
   - `git commit -m "commit message"`: Commit staged changes with a message.

5. **View Changes:**
   - `git status`: Show the status of changes.
   - `git diff`: Show changes between commits.

6. **Branching:**
   - `git branch`: List all branches.
   - `git branch [branch_name]`: Create a new branch.
   - `git checkout [branch_name]`: Switch to a branch.
   - `git merge [branch_name]`: Merge changes from another branch into the current branch.

7. **Remote Repositories:**
   - `git remote -v`: Show remote repositories.
   - `git remote add origin [repository_url]`: Add a remote repository.

8. **Pull and Push:**
   - `git pull origin [branch_name]`: Pull changes from a remote repository.
   - `git push origin [branch_name]`: Push changes to a remote repository.

9. **Log:**
   - `git log`: Show commit logs.
   - `git log --oneline`: Show compact commit logs.

10. **Undo Changes:**
    - `git reset HEAD [file]`: Unstage changes.
    - `git checkout -- [file]`: Discard changes in the working directory.

11. **Tagging:**
    - `git tag [tag_name]`: Create a new tag.
    - `git tag -a [tag_name] -m "tag message"`: Create an annotated tag.

12. **Stash Changes:**
    - `git stash`: Stash changes in a dirty working directory.
    - `git stash apply`: Apply stashed changes.

13. **Revert Commits:**
    - `git revert [commit_hash]`: Revert a commit.

14. **Fetch Changes:**
    - `git fetch origin`: Fetch changes from a remote repository.

15. **Rename and Delete:**
    - `git mv [old_file] [new_file]`: Rename a file.
    - `git rm [file]`: Delete a file.

16. **Rebase:**
    - `git rebase [branch_name]`: Reapply commits on top of another branch.

17. **Interactive Rebase:**
    - `git rebase -i [commit_hash]`: Interactively rebase commits.

18. **Show Commit Details:**
    - `git show [commit_hash]`: Show details of a specific commit.

19. **Cherry-Pick:**
    - `git cherry-pick [commit_hash]`: Apply changes from a specific commit.

20. **Reflog:**
    - `git reflog`: Show a log of changes in the repository.

21. **Reset Hard:**
    - `git reset --hard [commit_hash]`: Reset to a specific commit, discarding changes.

22. **Configurations:**
    - `git config --global user.name "[your_name]"`: Set your username globally.
    - `git config --global user.email "[your_email]"`: Set your email globally.

23. **Fetch Specific Branch:**
    - `git fetch origin [branch_name]`: Fetch changes for a specific branch.

24. **Show Branches in Graphical View:**
    - `git log --graph --oneline --all`: Show branches in a graphical view.

25. **Create and Switch to a New Branch:**
    - `git checkout -b [new_branch_name]`: Create and switch to a new branch.

26. **Show Remote Branches:**
    - `git branch -r`: Show remote branches.

27. **Delete Remote Branch:**
    - `git push origin --delete [remote_branch_name]`: Delete a remote branch.

28. **Submodules:**
    - `git submodule add [repository_url] [path]`: Add a submodule.
    - `git submodule update --init --recursive`: Initialize and update submodules.

29. **Show Contributors:**
    - `git shortlog -s -n`: Show contributors and their commit counts.

30. **Search in Commit History:**
    - `git log -S "search_term"`: Search for a specific term in commit history.

31. **Stash Changes:**
    - `git stash`: Stash changes in the working directory.

32. **List Stashes:**
    - `git stash list`: List all stashes.

33. **Apply Stash:**
    - `git stash apply [stash_name]`: Apply a stash.

34. **Drop Stash:**
    - `git stash drop [stash_name]`: Drop a stash.

35. **Pop Stash:**
    - `git stash pop`: Apply and drop the latest stash.

36. **Diff Stash:**
    - `git stash show -p [stash_name]`: Show the changes in a stash.

37. **Rename Branch:**
    - `git branch -m [new_branch_name]`: Rename the current branch.

38. **Merge Branch Into Current Branch:**
    - `git merge [branch_name]`: Merge another branch into the current branch.

39. **Merge Branch and Edit Commit Message:**
    - `git merge --edit [branch_name]`: Merge and edit the commit message.

40. **Log with Graph:**
    - `git log --graph --oneline --all --decorate`: Show a detailed log with a graph.

41. **Find Files in Repository:**
    - `git ls-files`: List all tracked files in the repository.

42. **File History:**
    - `git log [file_path]`: Show the commit history of a specific file.

43. **Show Changes in a File:**
    - `git diff [file_path]`: Show changes in a specific file.

44. **Blame:**
    - `git blame [file_path]`: Show who last modified each line of a file.

45. **Undo Last Commit:**
    - `git reset --soft HEAD^`: Undo the last commit, keeping changes staged.
Certainly! Here are 5 more Git commands:

46. **List Remote Repositories:**
    - `git remote -v`: List remote repositories and their URLs.

47. **Fetch Changes from Remote:**
    - `git fetch [remote_name]`: Fetch changes from a remote repository.

48. **Pull Changes from Remote:**
    - `git pull [remote_name] [branch_name]`: Pull changes from a remote repository.

49. **Set Upstream Branch:**
    - `git branch --set-upstream-to=[remote_name]/[remote_branch]`: Set the upstream branch for the current local branch.

50. **Cherry-pick a Commit:**
    - `git cherry-pick [commit_hash]`: Apply a specific commit onto the current branch.
