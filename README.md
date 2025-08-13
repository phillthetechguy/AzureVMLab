<h1>Creating a VM on Azure</h1>



<h2>Description</h2>
This project consists of me creating and configuring the settings of a Virtual Machine in Azure. This is a step by step documentation of everything i did to set up and deploy the VM for this project. 
<br />


<h2>Utilities Used</h2>

- <b>Windows RDP (Windows App)</b>



<h2>Environments Used </h2>

- <b>Windows Server 2022</b>
- <b>Azure Cloud</b>

<h2>Lab walk-through:</h2>

<p align="center">
1. Once i signed into Azure portal i went and created a Resource Group: <br/>
<img src="https://i.imgur.com/J0be2Th.png" height="80%" width="80%" alt=" Azure VM Steps"/>
<br />
<br />
2. When creating the resource group i created a name, chose region and clicked create:  <br/>
<img src="https://i.imgur.com/K1DpiwS.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
3. After group is created i made sure it was actually showing up and region was correct: <br/>
<img src="https://i.imgur.com/ycvITsp.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
4. Next i went into 'Virtual Machines' and created a VM:  <br/>
<img src="https://i.imgur.com/DWYCPvZ.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
5. I made sure my group was the one i created along with naming my VM and making sure the region was correct:  <br/>
<img src="https://i.imgur.com/EzJhgvy.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
6. Next i set my image to 'Windows server 2022' and size to 'Standard_B1s'(Both Free Tier and sufficent for basic testing):  <br/>
<img src="https://i.imgur.com/QoumDHQ.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
7. Set username and password for the VM and also made sure the correct port was being used (3389 for RDP):  <br/>
<img src="https://i.imgur.com/ogMD3O0.png" height="80%" width="80%" alt="Azure VM Steps"/>
 <br />
 <br />
8. I used the default settings for the OS disk (again just deploying the machine) :  <br/>
<img src="https://i.imgur.com/WCW16IX.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
9. Made sure a new VNet and subnet were created automatically and made sure the port was correct as well:  <br/>
<img src="https://i.imgur.com/TJUzhTt.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
10. After clicking 'Review + Create' i made sure the validation passed and then deployed the machine:  <br/>
<img src="https://i.imgur.com/bZsUBI2.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
11. once machine was deployed i made sure it was up and working :  <br/>
<img src="https://i.imgur.com/pT6GY6h.png" height="80%" width="80%" alt="Azure VM Steps"/>
<br />
<br />
12. From there i hit connect, downloaded the RDP file, launched my windows app, signed in using the credentials i created and here is the screenshot of the VM live :  <br/>
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
