# Additional Git commands

1. Clone a Repository:
   ```bash
   git clone URL_OF_REPOSITORY
   ```

2. Check the Status of Your Repository:
   ```bash
   git status
   ```

3. Add Changes to the Staging Area:
   ```bash
   git add <file-or-directory>
   ```

4. Commit Changes with a Message:
   ```bash
   git commit -m "commited message"
   ```

# Branching and Merging


1. Create a New Branch:
   ```bash
   git branch <branch-name>
   ```

2. Switch to a Different Branch:
   ```bash
   git checkout <branch-name>
   ```

3. Create and Switch to a New Branch:
   ```bash
   git checkout -b <branch-name>
   ```

4. Merge a Branch into the Current Branch:
   ```bash
   git checkout -b <branch-name>
   ```

5. Delete a Branch:
   ```bash
   git branch -d <branch-name>
   ```

# Remote Repositories   

1. Add a Remote Repository:
   ```bash
   git remote add origin URL_OF_REMOTE_REPOSITORY
   ```

2. View Remote Repositories:
   ```bash
   git remote -v
   ```

3. Push Changes to a Remote Repository:
   ```bash
   git push origin <branch-name>
   ```

4. Pull Changes from a Remote Repository:
   ```bash
   git pull origin <branch-name>
   ```

5. Fetch Changes from a Remote Repository:
   ```bash
   git fetch origin
   ```

# Reverting and Resetting

1. Revert a Commit by Creating a New Commit:
   ```bash
   git revert <commit-hash>
   ```

2. Reset to a Specific Commit (discarding all changes after):
   ```bash
   git reset --hard <commit-hash>
   ```

3. Reset to a Specific Commit (keeping changes in the working directory):
   ```bash
   git reset --soft <commit-hash>
   ```

4. Stash Uncommitted Changes:
   ```bash
   git stash
   ```

5. Apply the Latest Stash:
   ```bash
   git stash apply
   ```

6. List All Stashes:
   ```bash
   git stash list
   ```  

7. Clear All Stashes:
   ```bash
   git stash clear
   ```

# Viewing and Comparing Changes

1. Show Changes in the Working Directory:
   ```bash
   git diff
   ```

2. Show Changes Between Staged and Last Commit:
   ```bash
   git diff --cached
   ```  

3. Show a Specific Commit:
   ```bash
   git show <commit-hash>
   ```

4. Compare Two Branches:
   ```bash
   git diff <branch-1> <branch-2>
   ```

