Proxmox Automation

automatically spin up VMs on proxmox.

Prerequistes:

-Proxmox server
-VM template stored on proxmox server
-install ansible 


Step 1:Copy Repository


Step 2: create a vault.yml file with the password of the user account you will ssh into. .
	api_password: <Insert password> 

Step 3: create an inventory.ini file with server IP. 
