# Undo the Last Commit

1. Reset to the Previous Commit:
   ```bash
   git reset --soft HEAD~1
   ```

2. Unstage the Changes (if needed):
   ```bash
   git reset HEAD .
   ```

3. Push the Changes to the Remote Repository:
   ```bash
   git push origin master --force
   ```

# Remove the Last Created File and Keep the Commit History


4. Commit Changes with a Message:
   ```bash
   git commit -m "commited message"
   ```

# Branching and Merging


1. Remove the File:
   ```bash
   git rm <file-name>
   ```

2. Commit the Changes:
   ```bash
   git commit -m "Remove <file-name>"
   ```

3. Push the Changes to the Remote Repository:
   ```bash
   git push origin master
   ```

