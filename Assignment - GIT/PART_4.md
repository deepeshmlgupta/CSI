# Steps to Resolve Merge Conflicts


1. Fetch the Latest Changes from Remote:
   ```bash
   git fetch origin
   ```

2. Merge the Branches:
   ```bash
   git checkout master
   git merge feature-branch
   ```

3. Identify Conflicted Files:
   ```bash
   git status
   ```

4. Open and Resolve Conflicted Files:
  Open each conflicted file in a text editor and look for conflict markers (<<<<<<<, =======, and >>>>>>>). Edit the  files to resolve the conflicts by deciding which changes to keep.
   ```bash
   <<<<<<< HEAD
   This is content from the master branch.
   =======
   This is content from the feature branch.
   >>>>>>> feature-branch
   ```
   Remove the conflict markers and make necessary changes to resolve the conflicts.


5. Mark the Conflicts as Resolved:
   ```bash
   git add <conflicted-file>
   ```
   Repeat this for each conflicted file.

6. Commit the Merge:
   ```bash
   git commit
   ```
   Git might automatically generate a commit message, in which we can edit if needed.

7. Push the Changes:
   ```bash
   git push origin master
   ```

