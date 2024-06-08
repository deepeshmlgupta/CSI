# Deploy Linux and Windows virtual machines and access them using SSH and RDP  

# Through SSH

1. Sign in to the Azure Portal:

2.  Click on "Virtual machines"

3. Click on "Create" and then "Azure virtual machine".

4. Open Port 22 for SSH:

5. Access the Linux VM via SSH: (Use the downloaded private key to SSH into the VM:)
   ```bash
   ssh -i path_to_your_private_key azureuser@<Linux_VM_Public_IP>
   ```
# Through RDP

1. Sign in to the Azure Portal:

2.  Click on "Virtual machines"

3. Click on "Create" and then "Azure virtual machine".

4. Open Port 3389 for SSH:

5. Access the Windows VM via RDP:
- On your local machine, open the Remote Desktop Connection client.
- Enter the public IP address of the Windows VM.
-  When prompted, enter the username and password you specified during the VM creation.
