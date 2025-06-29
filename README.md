# Azure-VM-and-Web-Server-Deployment-with-Bastion-Access


<h2>Project Details</h2>
This lab focused on building a secure and accessible web server infrastructure on Microsoft Azure. The hands-on project provided me with a structured environment to go through the complete lifecycle of deploying a virtual machine, securing network access, and hosting a web application (Nextcloud). It provided practical experience in cloud infrastructure provisioning, network security configuration, and remote server management using Azure-native tools.<br />
<br />

**Tasks Breakdown:**

**Task 1: Introduction to OWASP ZAP**

Began with an overview of OWASP ZAP, its role in web application security, and its importance for penetration testers and security professionals. This step laid the groundwork for understanding the tool’s capabilities.

**Task 2: Scanning a Website for Vulnerabilities**

Explored the OWASP ZAP interface and performed a basic vulnerability scan on a target website. This task demonstrated how to initiate scans and interpret the results.

**Task 3: Analyzing Scan Results and Generating Reports**

Reviewed the scan output to identify potential vulnerabilities. Generated a structured vulnerability report to summarize findings, which is essential for communicating risks to stakeholders.

**Task 4: Configuring FoxyProxy in Firefox**

Set up FoxyProxy, a Firefox extension, to route browser traffic through OWASP ZAP. This configuration enabled passive scanning of web traffic during normal browsing.

**Task 5: Discovering Hidden Files and Directories**

Used a dictionary list within OWASP ZAP to brute-force and discover hidden files and directories on the web server. This technique is useful for uncovering unlinked or sensitive resources.

**Task 6: Crawling and Spidering Websites**

Utilized ZAP’s spidering functionality to crawl the target website, identifying all accessible links and URLs. This helps in mapping the application’s structure and attack surface.

**Task 7: Intercepting and Modifying Web Requests**

Used OWASP ZAP as a web proxy to intercept, view, and modify HTTP requests. This task simulated how attackers might manipulate requests to provoke unexpected behavior or exploit vulnerabilities.


<br />

**Key Takeaways:**

This lab provided practical experience in using OWASP ZAP for web application security testing. Key skills developed include:

- Performing vulnerability scans and interpreting results
- Configuring browser proxies for passive scanning
- Discovering hidden resources using dictionary lists
- Crawling websites to map attack surfaces
- Intercepting and manipulating web traffic for deeper analysis
  
These skills are essential for anyone pursuing a career in cybersecurity or penetration testing.
<br />


<h2>Softwares and Utilities Used</h2>

- <b>OWASP ZAP: Used for scanning, crawling, intercepting, and analyzing web application traffic.</b>
- <b>FoxyProxy: Firefox extension used to route browser traffic through ZAP.</b>
- <b>Dictionary Lists: Used for brute-force discovery of hidden files and directories.</b> 

  

<h2>Environments Used </h2>

- <b>Linux Desktop Environment: The lab was conducted in a Linux-based environment, emphasizing the use of open-source tools and platforms for cybersecurity tasks.

</b>

<h2>Program walk-through:</h2>




<p align="center">
Task 2: Scanning a Website for Vulnerabilities <br/>
<br />
<br />
<img src="https://i.imgur.com/67Ne8qH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/scbJiKv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/cquaWlU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/GeCNW0W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/KhRbAyK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/bQVWPdG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/GDRuIHw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/RE9vvXo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/e7lNt5x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/dqLgi9c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/qBe49w5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
  
<p align="center">
Task 3: Analyzing Scan Results and Generating Reports <br/>
<br />
<br />
<img src="https://i.imgur.com/Tsu5EZ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/PdEm2jA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/t8gfST2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/jx28roy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/brDYiHX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/CIH89Bt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/909231k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Ws91gPG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/zaG3I8Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/RCwSIz2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<br />
<br />
<br />
Task 4: Configuring FoxyProxy in Firefox  <br/>
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
Task 5: Discovering Hidden Files and Directories  <br/>
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
Task 6: Crawling and Spidering Websites  <br/>
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
Task 7: Intercepting and Modifying Web Requests  <br/>
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
