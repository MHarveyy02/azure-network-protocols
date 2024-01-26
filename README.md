<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Deploy Azure Virtual Machines that you want to observe and experiment with. Ensure that they are running and accessible.
Install Wireshark on your local machine or a separate VM that has network connectivity to the Azure VMs.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to the Azure Portal and access the NSG associated with your Azure VMs.
Experiment with NSG rules by adding or modifying them. For example, you might create rules to allow or deny specific protocols, ports, or IP ranges.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the local machine where Wireshark is installed, open the application.
Start a new capture interface and select the network interface through which traffic between your local machine and Azure VMs flows.
Begin capturing network traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Perform operations on your Azure VMs that involve network communication. For example, initiate a ping from one VM to another, access a web service, or SSH into a VM.
Observe the captured packets in Wireshark as they represent the network traffic to and from the Azure VMs.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Stop the packet capture in Wireshark.
Analyze the captured packets to understand the different types of traffic, including protocols, source and destination IP addresses, ports, and any communication anomalies.
Correlate your observations with the NSG rules to see how they impact the allowed or denied traffic.
</p>
<br />
