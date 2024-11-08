<h1>SIEM Lab Using Azure Sentinel</h1>

<h2>Description</h2>
In this lab I have setup a SIEM using Azure Sentinel and Azure virtual machines. I have also created a live map that logs and displays where threats are coming from based upon failed login attempts. The purpose of this lab is to gain hands-on experience setting up and utilizing a SIEM in order to get practice tracking potential threats and learning about what to look out for. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Azure</b>
- <b>Azure Virtual Machines</b>
- <b>Azure Logs</b>
- <b>Azure Sentinel</b>

<h2>Lab walk-through:</h2>

<p align="center">
Creating Network Security Group for Honeypot Virtual Machine: <br/>
<img src="https://i.imgur.com/El0I2O1.png" height="80%" width="80%" alt="NSG Creation"/>
<br />
<br />
Creating Custom Log using Log Analytics Workspace to pull "Failed RDP" requests from VM:  <br/>
<img src="https://i.imgur.com/b9L1YzR.png" height="80%" width="80%" alt="Log Creation"/>
<br />
<br />
Configuring Network Security Group to Allow any and all traffic: <br/>
<img src="https://i.imgur.com/7H6lZ1s.png" height="80%" width="80%" alt="Allow All"/>
<br />
<br />
Removing Firewall from Virtual Machine:  <br/>
<img src="https://i.imgur.com/kX39Ct8.png" height="80%" width="80%" alt="Remove Firewall"/>
<br />
<br />
Powershell Script to export logs from the Virtual Machine:  <br/>
<img src="https://i.imgur.com/qPqhBj8.png" height="80%" width="80%" alt="Powershell script"/>
<br />
<br />
Virtual Machnine Logs being pulled using Azure Logs:  <br/>
<img src="https://i.imgur.com/ryX5j8Q.png" height="80%" width="80%" alt="Log Pulls"/>
<br />
<br />
Using a script to extract the raw data from the logs:  <br/>
<img src="https://i.imgur.com/kqqLZLY.png" height="80%" width="80%" alt="Raw Data"/>
 <br />
 <br />
Creating workbook in Azure Sentinel to create a world map:  <br/>
<img src="https://i.imgur.com/mJ1M6Au.png" height="80%" width="80%" alt="Workbook"/>
<br />
<br />
World Map Showing All Failed Login Attempts From Around the World Using IP Geolocator:  <br/>
<img src="https://i.imgur.com/wLy7dIj.png" height="80%" width="80%" alt="Failed Login Map"/>
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
