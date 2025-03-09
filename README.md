<h1>Azure Home SOC – Cloud-Based Honeypot & Sentinel Integration</h1>


<h2>Description</h2>
Implemented a foundational Security Operations Center (SOC) in Microsoft Azure using a free subscription. This project involves:

  - Deploying a virtual machine as an internet-facing honeypot.
  - Configuring a Log Analytics Workspace to centralize and forward logs.
  - Integrating Microsoft Sentinel to query failed login attempts, locate attack sources, and build a dynamic attack map.
    
This hands-on project demonstrates practical cloud cybersecurity operations, log analysis, and threat detection, making it an ideal learning tool for both beginners and seasoned professionals.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Microsoft Sentinel</b>

<h2>Environments Used </h2>

- <b>Windows 10 Virtual Machine</b> 

<h2>Project walk-through:</h2>

<p align="center">
Set up resources in Azure: <br/>
<img src="https://i.imgur.com/I412gar.png" height="80%" width="80%" alt="Azure Resource Group"/>
<br />
<br />
Created honeypot by opening the firewall to allow any connection:  <br/>
<img src="https://i.imgur.com/P1BYkPX.png" height="60%" width="60%" alt="Firewall Configuration"/>
<br />
<br />
Observed logs on the VM: <br/>
<img src="https://i.imgur.com/MNm5PQ8.png" height="80%" width="80%" alt="Log Report on Virtual Machine"/>
<br />
<br />
Forwarded logs to Sentinel to create an attack map: <br />
<img src="https://i.imgur.com/veMAoAu.png" height="80%" width="80%" alt="Visual of Attack Map"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>


