<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://youtu.be/HlLjxre7rPI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Two Virtual Machine
- Connect to Remote Desktop Connection
- Run Wireshark
- Observe Wireshark Traffic

<h2>Actions and Observations</h2>

![Step 1](https://github.com/BenW618/azure-network-protocols/assets/140227052/d01c782c-992d-479f-ac2c-ef5bf3efaea8)

</p>
<p>
The first thing I did was create the resources. I created my resource group and virtual machines. My first virtual machine was Windows 10 and my second virtual machine was Linux. To watch me do this step by step, watch the youtube video linked above. The timestamps are from 00:00 to 5:00.
</p>
<br />

![Step 2](https://github.com/BenW618/azure-network-protocols/assets/140227052/9976c80a-5c61-458d-be5f-fe639db2ee30)

</p>
<p>
Next, I used Remote Desktop to connect to the Windows 10 virtual machine. The timestamps are from 5:00 to 6:28.
</p>
<br />

![Step 3 3](https://github.com/BenW618/azure-network-protocols/assets/140227052/899f6a33-014d-49af-b6d2-75108a6bc9ad)

</p>
<p>
Then, I installed Wireshark on the Windows 10 virtual machine. The timestamps are from 6:28 to 10:10.
</p>
<br />

![Step 5](https://github.com/BenW618/azure-network-protocols/assets/140227052/4b2f9095-3f04-4767-875e-41f3ed39417b)

</p>
<p>
Once Wireshark was installed, I started to observe traffic through the virtual machines. I observed ICMP, SSH, DHCP, DNS, and RDP traffic. The timestamps are from 10:10 to the rest of the video.
</p>
<br />
