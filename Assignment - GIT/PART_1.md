Initialize a Local Repository:
   ```bash
   git init
   ```

Create a File and Add Some Content:
   ```bash
   echo "Hello, World!" > example.txt
   ```

Add the File to the Staging Area:
   ```bash
   git add example.txt
   ```

Commit the Changes:
   ```bash
   git commit -m "Add example.txt with initial content"
   ```

Push to the Master Branch:
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

