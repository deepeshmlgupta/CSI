# Repository Setup Guide

This guide will help you create a new branch, commit and push changes to the new branch, and merge it with the master branch using a pull request.

## Steps

1. Initialize a Local Repository:
   ```bash
   git init
   ```

2. Add a Remote Repository:
   ```bash
   git remote add origin URL_OF_REMOTE_REPOSITORY
   ```

3. Create a New Branch
   ```bash
   git checkout -b new-feature
   ```

4. Create a File and Add Content
   ```bash
   echo "Hello, World!" > example.txt
   ```

5. Add the File to the Staging Area:
   ```bash
   git add example.txt
   ```

5. Commit the Changes:
   ```bash
   git commit -m "Add example.txt with initial content"
   ```

6. Push to the Master Branch:
   ```bash
   git push -u origin new-feature
   ```

8. Create a Pull Request
Go to your remote repository on GitHub and create a pull request to merge the new-feature branch into the master branch.

9. Merge the Pull Request
Once the pull request is created, review the changes and merge it into the master branch.

10. Complete sequence of the commands:
   ```bash
   git init
   git remote add origin URL_OF_YOUR_REMOTE_REPOSITORY
   git checkout -b new-feature
   echo "Hello, World!" > example.txt
   git add example.txt
   git commit -m "Add example.txt with initial content"
   git push -u origin new-feature
   ```


