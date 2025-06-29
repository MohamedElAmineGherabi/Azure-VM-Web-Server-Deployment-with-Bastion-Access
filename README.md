# Azure-VM-and-Web-Server-Deployment-with-Bastion-Access


<h2>Project Details</h2>
This lab focused on building a secure and accessible web server infrastructure on Microsoft Azure. The hands-on project provided me with a structured environment to go through the complete lifecycle of deploying a virtual machine, securing network access, and hosting a web application (Nextcloud). It provided practical experience in cloud infrastructure provisioning, network security configuration, and remote server management using Azure-native tools.<br />
<br />

**Tasks Breakdown:**

**Task 1: Creating a Resource Group**

The lab began with the creation of a dedicated Azure Resource Group to logically organize and manage all related resources. This foundational step ensured that all components of the deployment were grouped for easier monitoring, billing, and lifecycle management.

**Task 2: Setting Up a Virtual Network and Subnet**

A custom Virtual Network (VNet) was created along with a subnet to define the IP address space and network segmentation. This step laid the groundwork for secure communication between Azure resources.

**Task 3: Securing the Subnet with a Network Security Group (NSG)**

A Network Security Group was deployed and associated with the subnet to enforce inbound and outbound traffic rules. This task emphasized the importance of perimeter security and demonstrated how to restrict access to only necessary ports and protocols.

**Task 4: Deploying Azure Bastion for Secure VM Access**

Azure Bastion was configured to enable secure, browser-based RDP/SSH access to the virtual machine without exposing it to the public internet. This task highlighted best practices in remote access security.

**Task 5: Creating an Ubuntu Virtual Machine**

An Ubuntu Server VM was provisioned within the secured subnet. This step involved selecting the appropriate image, size, authentication method, and associating the VM with the previously created NSG and VNet.

**Task 6: Installing Nextcloud via SSH**

Using Azure Bastion, an SSH session was initiated to the Ubuntu VM. Nextcloud, a self-hosted productivity platform, was installed and configured. This task provided hands-on experience with Linux server administration and web application deployment.

**Task 7: Publishing the Web Server with a Public IP**

A public IP address was assigned to the VM to make the Nextcloud instance accessible over the internet. This step involved configuring DNS and ensuring the NSG allowed HTTP/HTTPS traffic.

**Task 8: Creating a DNS Label**

To simplify access, a DNS label was created and associated with the public IP. This allowed users to reach the Nextcloud server using a friendly domain name instead of a raw IP address.

<br />

**Key Takeaways:**

This lab provided a comprehensive walkthrough of deploying a secure, internet-accessible web application on Azure. Key skills developed include:

- Provisioning and managing Azure infrastructure components
- Configuring virtual networks and subnets
- Implementing network security using NSGs
- Using Azure Bastion for secure remote access
- Installing and configuring web applications on Linux VMs
- Publishing services with public IPs and DNS labels

These skills are essential for cloud engineers, DevOps professionals, IT administrators, as well as Cybersecurity professionals working with Azure environments.
<br />


<h2>Softwares and Utilities Used</h2>

- <b>Microsoft Azure Portal: Used for provisioning and managing all cloud resources.</b>
- <b>Azure Bastion: Enabled secure, browser-based SSH access to the VM.</b>
- <b>Ubuntu Server: Operating system used for hosting the Nextcloud application.</b>
- <b>Nextcloud: Open-source web application installed on the VM for file sharing and collaboration.</b> 


  

<h2>Environments Used </h2>

- <b>Azure Cloud Environment: All tasks were performed within the Azure ecosystem, leveraging its native tools and services for infrastructure, networking, and security.

</b>

<h2>Program walk-through:</h2>




<p align="center">
Task 1: Creating a Resource Group <br/>
<br />
<br />
<img src="https://i.imgur.com/IuKZ9pg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/AvlV1ke.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/4qXpyAi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/zkzdioE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/xwjXv0o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/2ieH3Oi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p align="center">
Task 2: Setting Up a Virtual Network and Subnet <br/>
<br />
<br />
<img src="https://i.imgur.com/7J4tkMc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/aEQ0t9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Xuk739S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/E0R7zrJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/fCXz9Lp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/WiTvVJD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/LGU6o5a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ovafc8O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/kMlvsGX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/IyI1Obm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/EvJ5Zlt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
  
<p align="center">
Task 3: Securing the Subnet with a Network Security Group (NSG) <br/>
<br />
<br />
<img src="https://i.imgur.com/Wnm1bmq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/PPMtGVt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/IUR7lM7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/xljaI2w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/A95YTfw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/xXZw89P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/N1TBLNX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/vXWFHMh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>




<br />
<br />
<br />
Task 4: Deploying Azure Bastion for Secure VM Access  <br/>
<br />
<img src="https://i.imgur.com/7n9oWbu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/qo68mwV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/AzL9dZW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/t4AKnam.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/cz0kvbN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/FKZQlgv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/RySg02S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/yQIvR6c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<br />


<br />
<br />
Task 5: Creating an Ubuntu Virtual Machine  <br/>
<br />
<img src="https://i.imgur.com/chnDLEI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/GPO040c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/I1uID1Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/hUwdXx1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/p6jyvgD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/yTstuRF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
<br />
Task 6: Installing Nextcloud via SSH  <br/>
<br />
<img src="https://i.imgur.com/A9nMCot.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
<img src="https://i.imgur.com/hgWzd5P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
<img src="https://i.imgur.com/ldz4bSN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
<img src="https://i.imgur.com/hNaiE5W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
<img src="https://i.imgur.com/3PeRKNu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<br />
<br />
<br />
Task 7: Publishing the Web Server with a Public IP  <br/>
<br />
<br />
<img src="https://i.imgur.com/MwC7DM9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Hk9qN7G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/2jITYlN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/7pPQ2r2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Rd7a0SD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/KM0aUIf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/gZUsu6I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/qcR7QZj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/MG4J5OI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/8e4UYPZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/waVocN0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/n8NYKRe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/iIDydjI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
Task 8: Creating a DNS Label  <br/>
<br />
<br />
<img src="https://i.imgur.com/MwC7DM9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Hk9qN7G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
<br />
<br />
<img src="https://i.imgur.com/cZjZ1uC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />










<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
