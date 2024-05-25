Create a new user
 ```bash
   sudo useradd newuser
   ``` 


Set a password for the new user
 ```bash
   sudo passwd newuser
   ``` 


Create a new group
 ```bash
   sudo groupadd newgroup
   ``` 


Add the new user to the new group
 ```bash
   sudo usermod -aG newgroup newuser
   ``` 


Change the new user's primary group to the new group
 ```bash
   sudo usermod -g newgroup newuser
   ``` 


Change ownership of the home directory to the new user
 ```bash
   sudo chown newuser:newgroup /home/newuser
   ``` 


Change permissions of the home directory
 ```bash
   sudo chmod 755 /home/newuser
   ``` 


Lock the new user's account
 ```bash
   sudo usermod -L newuser
   ``` 


Unlock the new user's account
 ```bash
   sudo usermod -U newuser
   ``` 


Change the new user's shell
 ```bash
   sudo usermod -s /bin/bash newuser
   ``` 


Delete the new user (without removing their home directory)
 ```bash
   sudo userdel newuser
   ``` 


Delete the new user and their home directory
 ```bash
   sudo userdel -r newuser
   ``` 


Delete the new group
 ```bash
   sudo groupdel newgroup
   ``` 
