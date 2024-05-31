# Repository Setup Guide

This guide will help you set up a remote repository on your local machine, add a file, commit the changes, and push to the master branch.

## Steps

1. Initialize a Local Repository:
   ```bash
   git init
   ```

2. Create a File and Add Some Content:
   ```bash
   echo "Hello, World!" > example.txt
   ```

3. Add the File to the Staging Area:
   ```bash
   git add example.txt
   ```

4. Commit the Changes:
   ```bash
   git commit -m "Add example.txt with initial content"
   ```

5. Push to the Master Branch:
   ```bash
   git push -u origin master
   ```

Add a Remote Repository:
   ```bash
   git init
   git remote add origin URL_OF_YOUR_REMOTE_REPOSITORY
   echo "Hello, World!" > example.txt
   git add example.txt
   git commit -m "Add example.txt with initial content"
   git push -u origin master
   ```

