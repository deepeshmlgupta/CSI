Create a file
   ```bash
   touch file.txt
   ```
   
Assign permissions: read, write, execute for owner; read, execute for group; read for others
   ```bash
   chmod 754 file.txt
   ```
   
Change permissions: read, write for owner; read for group; no permissions for others
 ```bash
   chmod 640 file.txt
   ```

Change permissions: read, write, execute for owner; read, write for group; no permissions for others
 ```bash
   chmod 760 file.txt
   ```  


Assign permissions: read, write for owner; read for group; no permissions for others
 ```bash
   chmod 644 file.txt
   ```  


Assign permissions: read, write, execute for owner; execute for group and others
 ```bash
   chmod 711 file.txt
   ```


Assign permissions: read, execute for owner, group, and others
 ```bash
   chmod 555 file.txt
   ```  


Assign permissions: no permissions for anyone
 ```bash
   chmod 000 file.txt
   ```  


Assign permissions: read, write, execute for owner; read, write for group; execute for others
 ```bash
   chmod 761 file.txt
   ```  

Assign permissions: read, execute for owner; no permissions for group and others
 ```bash
   chmod 500 file.txt
   ```  
