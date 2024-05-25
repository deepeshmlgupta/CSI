Display system information
 ```bash
   uname -a
   ```


Display current date and time
 ```bash
   date
   ```


Display disk usage in human-readable format
 ```bash
   df -h
   ```


Display memory usage
 ```bash
   free -h
   ```


Display running processes
 ```bash
   ps aux
   ```


Search for a specific process
 ```bash
   ps aux | grep process_name
   ```


Display the last 10 lines of a file
 ```bash
   tail filename.txt
   ```


Continuously monitor the end of a file
 ```bash
   tail -f filename.txt
   ```


Display the first 10 lines of a file
 ```bash
   head filename.txt
   ```


Count lines, words, and characters in a file
 ```bash
   wc filename.txt
   ```


Search for a pattern in a file
 ```bash
   grep 'pattern' filename.txt
   ```


Recursively search for a pattern in files within a directory
 ```bash
   grep -r 'pattern' /path/to/directory
   ```


Find files and directories
 ```bash
   find /path/to/search -name 'filename'
   ```


Display a file with pagination
 ```bash
   less filename.txt
   ```


Show current logged in users
 ```bash
   who
   ```


Show user details
 ```bash
   id username
   ```


Switch to another user
 ```bash
   ssu - username
   ```


Execute a command as another user
 ```bash
   sudo -u username command
   ```


Change file ownership
 ```bash
   sudo chown owner:group filename
   ```


Change file permissions
 ```bash
   chmod 755 filename
   ```


Create a symbolic link
 ```bash
   ln -s /path/to/original /path/to/link
   ```


Create a hard link
 ```bash
   ln /path/to/original /path/to/link
   ```


Archive files using tar
 ```bash
   tar -cvf archive_name.tar /path/to/directory_or_files
   ```


Extract files from a tar archive
 ```bash
   tar -xvf archive_name.tar
   ```


Compress files using gzip
 ```bash
   gzip filename
   ```


Decompress files using gzip
 ```bash
   gunzip filename.gz
   ```


Compress files using bzip2
 ```bash
   bzip2 filename
   ```


Decompress files using bzip2
 ```bash
   bunzip2 filename.bz2
   ```


Compress files using zip
 ```bash
   zip archive_name.zip file1 file2
   ```


Decompress files using zip
 ```bash
   unzip archive_name.zip
   ```


Display disk usage of files and directories
 ```bash
   du -sh /path/to/directory_or_file
   ```


Show listening network ports and associated programs
 ```bash
   sudo netstat -tuln
   ```


Display routing table
 ```bash
   route -n
   ```


Show network interface configuration
 ```bash
   ifconfig
   ```
ifconfig

Display active network connections
 ```bash
   sudo lsof -i
   ```


Download files from the internet
 ```bash
   wget https://css4.pub/2015/icelandic/dictionary.pdf
   ```


# Upload or download files using SCP (Secure Copy)
 ```bash
   scp /path/to/local/file user@remote_host:/path/to/remote/file
   scp user@remote_host:/path/to/remote/file /path/to/local/file
   ```


# Synchronize files and directories between two locations
 ```bash
   rsync -avz /path/to/source user@remote_host:/path/to/destination
   ```

