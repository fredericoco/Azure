# Azure
## What is Azure?
### Creating a windows VM with Azure 
In order to create a windows virtual machine follow theses steps:
- Click on create a resourse, and then create virtual machine
- Under resource group, give it a good group name
- Under instance details, choose a region (UK South), for a basic VM availaibility zones is not necessary, and availability zones is not necessary.
- Security type can be chosen as standard, and choose a windows image (Windows Server 2019 Datacenter)
- For size go for Standard D2as_v4
- Create a username and password for this account
- For inbound port rules, allow selected ports, choose RDP (3389)
- In the disk have an SSD and a standard hardrive.
- Click on review and create
- Download the RDP file and put in your username and password you created earlier.
- Well done you've accessed your VM.
  
When you're in the virtual machine pin the server manager to the taskbar for convinience.

 Open a command terminal by typing cmd into the start bar. Type `ipconfig`. Go to local server, click on the ethernet link. Disable IPV 6 and go to the properties of IPV 4. Go to the DNS server address edit, put the `IPv4 Address` into the preffered DNS server in there. In the alternate DNS server put `8.8.8.8`.