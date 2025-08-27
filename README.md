<h1>Creating a VM on Azure</h1>



<h2>Description</h2>
This project consists of me creating and configuring the settings of a Virtual Machine in Azure. This is a step by step documentation of everything i did to set up and deploy the machine for this project. 
<br />


<h2>Utilities Used</h2>

- <b>Windows RDP (Windows App)</b>



<h2>Environments Used </h2>

- <b>Windows Server 2022</b>
- <b>Azure Cloud</b>

<h2>Video walk-through:</h2>



https://github.com/user-attachments/assets/80ab4f41-f8a0-49ef-9353-47fcea481b37


<h2>Screenshot walk-through:</h2>

<p align="center">
1. Once i signed into Azure portal i went and created a Resource Group: <br/>
<img width="1916" height="847" alt="s1" src="https://github.com/user-attachments/assets/d955068a-cc1c-4f63-832b-98324d009372" />
<br />
<br />
2. When creating the resource group i created a name, chose region and clicked create:  <br/>
<img width="1914" height="846" alt="s2" src="https://github.com/user-attachments/assets/4d989b6c-3058-44b7-83ab-f29ee60c2cea" />
<br />
<br />
3. After group is created i made sure it deployed properly: <br/>
<img width="1916" height="846" alt="s3" src="https://github.com/user-attachments/assets/a549864a-1950-44ce-a4ea-47abc268a55f" />
<br />
<br />
4. Next i went into 'Virtual Machines' and started to create our VM:  <br/>
<img width="1912" height="844" alt="s4" src="https://github.com/user-attachments/assets/fb6630d9-9c39-4fbd-8f80-9c7fde3206c6" />
<br />
<br />
5. I made sure my group was the one i created along with naming my VM and making sure the region was correct:  <br/>
<img width="1914" height="844" alt="s5" src="https://github.com/user-attachments/assets/e64c756c-21e5-4ce9-8703-a2310567d01a" />
<br />
<br />
6. Next i set my image to 'Windows server 2022' and size to 'Standard_B1s'(Both Free Tier and sufficent for basic testing):  <br/>
<img width="1910" height="842" alt="s6" src="https://github.com/user-attachments/assets/d828fa24-80dd-43f1-8ed6-5fc01edd9578" />
<br />
<br />
7. Set username and password for the VM and also made sure the correct port was being used (3389 for RDP):  <br/>
<img width="1915" height="847" alt="s7" src="https://github.com/user-attachments/assets/80166630-dde9-4ade-8193-224f808243a7" />
 <br />
 <br />
8. Made sure a new VNet and subnet were created automatically and made sure the port was correct as well:  <br/>
<img width="1914" height="847" alt="s8" src="https://github.com/user-attachments/assets/cbff9564-3993-463e-93a9-ba9dd48e51d8" />
<br />
<br />
9. After clicking 'Review + Create' i made sure the validation passed and then clicked create:  <br/>
<img width="1911" height="846" alt="s9" src="https://github.com/user-attachments/assets/b09784f3-3edf-49b4-9fcb-2e9eea2f462b" />
<br />
<br />
10. once machine was validated i made sure deployment was correct :  <br/>
<img width="1914" height="845" alt="s10" src="https://github.com/user-attachments/assets/252373dc-054e-4653-9290-a684e84786ee" />
<br />
<br />
11. From there i hit connect, downloaded the RDP file, open my windows rdp app to log in :  <br/>
<img width="1914" height="845" alt="s11" src="https://github.com/user-attachments/assets/7e965f5a-8371-4d7f-b9cf-142a7d3ce230" />
<br />
<br />
12. Once credentials are confirmed this is what the main screen of our VM should look like :  <br/>
<img src="https://i.imgur.com/eyNAtZg.png" height="80%" width="80%" alt="Azure VM Steps"/>
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
