# Vitual Private Network (VPN)
<p align="center">
  
![image](https://github.com/user-attachments/assets/2ba68a7e-5591-4740-b9e7-951ee17fc7ec)


</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation ousing a VPN.<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>STEPS INCLUDED</h2>

- Step 1 - Locate Local IP
- Step 2 - Setting Up VM Using Azure
- Step 3 - Locating IP Through VM 
- Step 4 - Connecting to VPN Through VM
- Step 5 - Locating IP Through VPN 

<h2>Installation Steps</h2>

Step 1 - Locate your own personal IP address by going to "www.whatismyipaddress.com" which will be able to show you your local IP address. We will use this later as well. 

<p>
  
![ip laredo](https://github.com/user-attachments/assets/9bd420de-5f34-4532-b513-084c6e178659)

</p>
<p>

Next we will set up a virtual machine on Azure. 
<p>
</p>
<br />
<p>
</p>
<p>
</p>
<br />
<p>
</p>
<p>
Step 2 - Make a Virtual Machine in Microsoft Azure. 

<p>
  
![create a vm](https://github.com/user-attachments/assets/d3fb484a-ac15-44d1-b882-2f77782dc1dc)

</p>
<p>
  
</p>
<br />
Then select “Review and Create”, once it passes validation select “Create” at the bottom. 
</p>

<p>
</p>
<br />
<p>
</p>
<p>
</p>
<br />
<p>
</p>
<p>

Step 3 - Log Into your Virtual Machines Public IP Address on Remote Desktop
</p>

![looking at ip vm](https://github.com/user-attachments/assets/677a0c68-d8ca-4eaa-8e54-4c5b741ed71e)
![connecting to vm](https://github.com/user-attachments/assets/9ce00070-5884-4c4f-91cb-2cc708eec815)

<p>
</p>
<p>
</p>
</p>
</p>

Once logged in, we will open the web browser and again look up www.whatismyipaddress.com. 
<br />
When we look up the IP address for this VM we see that this VM is showing the location for Quincy, Washinton (since the VM we created is in region US West 2)  
</p>
<br />
<p>
  
![ip vm](https://github.com/user-attachments/assets/1c1b2cdf-416d-48dd-afea-8b8b1279a570)

</p>
<p>
</p>
<br />
<p>
</p>
<p>
</p>
<br />
<p>
</p>
<p>

Step 4 – CONNECTING TO VPN (Free Version)

Using the local computer go to protonvpn.com and create a free account.
<p>
Once you have logged into your Proton VPN account on the VM, you will select “Downloads” and choose to download the “Windows” version. Once the application Proton VPN is installed we will log in using the credentials we used when setting up a free account on Proton VPN. Then connect to the VPN through the installed app.
  
</p>
<br />


![vm vpn](https://github.com/user-attachments/assets/d5472c06-29fd-4b9e-b760-2f6297566ffc)

</p>
<p>

On the left hand side of the VPN you can see that I am connected to IP 146.70.230.118 (which is in Los Angeles, California)
</p>
<p>
</p>
<br />
<p>
</p>
<p>
</p>
<br />
<p>
</p>
<p>
Step 5 - Locating IP Through VPN

Next we will look at the IP again using the VM browser now that we have connected the VPN to Los Angeles, California. The website www.whatismyipaddress.com shows yet another IP address using the VPN from Los Angeles, California
  
</p>
<br />
<p>

![vm new ip vpn](https://github.com/user-attachments/assets/e1f6c073-0236-4498-8c37-485be492710f)

</p>
<p>
Looking at this exercise we see that we have utilized 3 different IP addresses just from your local computer to connect to the internet.
</p>
<p>
  
Home IP in Laredo, Tx: 35.146.225.126
<p>
Virtual Machine IP in Quincy, Washinton: 128.85.26.157
<p> 
Virtual Machine IP VPN in Los Angeles, California: 146.70.230.118
</p>
<br />
If you no longer need the VM, ensure to remove it from the Azure account for unwanted charges.

