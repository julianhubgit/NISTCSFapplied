<h1>Use the NIST CSF Cybersecurity Framework to respond to a security incident</h1>


<h2>Description</h2>
A company experienced a security event when all network services suddenly
stopped responding. The cybersecurity team found the disruption was caused
by a distributed denial of services (DDoS) attack through a flood of incoming
ICMP packets. The team responded by blocking the attack and stopping all
non-critical network services, so that critical network services could be
restored. Using the five key components of the NIST CSF Framework outline how to respond effectively to this security incident.
<br />


<h2>Languages and Utilities Used</h2>

- <b>NIST CSF Cybersecurity Framework</b> 


<h1>Program walk-through:</h1>



<h2 align="center">Identify: </h2>
  
A flood of ICMP pings was sent through to our network through an unconfigured firewall. This flood of ICMP packets caused the network to stop responding as it overloaded the system’s bandwidth, not allowing the system to be able to forward traffic. This was a DDoS ICMP flood attack by the malicious actor. 


<h2 align="center">Protect:</h2>

The system can further improve by configuring the firewall to block ICMP pings from external sources. A VPN can be used to encrypt data and company IP address so data cannot be used by malicious actors and ICMP attacks in the future will be much more difficult as IP addresses will be encrypted. 


<h2 align="center">Detect:</h2>

Double clicking the PC allows us to navigate to the Desktop tab and then to the IP Configuration.

<img src="https://i.imgur.com/7cESyrc.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Selecting DHCP for the IP Configuration heading will allow the PC to receive an IP address from the DHCP.

<img src="https://i.imgur.com/EYZAxa9.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/EYZAxa9.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Navigate to command line within the PC and enter the "ipconfig /all" prompt to verify the PC received an IPv4 address in the 192.168.0.x range.

<img src="https://i.imgur.com/iRrVV1X.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>


<h2 align="center">Configure the Laptop:</h2>

Double clicking the laptop will allow you to select the physical tab.

<img src="https://i.imgur.com/Kp46rci.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Power off the laptop by pressing the power off button. Remove the currently installed Ethernet copper module by clicking on the module on the side of the laptop and dragging it to the modules pane on the left. 
Install WPC300N module by clicking it in the modules pane and dragging it to the empty module on the laptop. Power on laptop.

<img src="https://i.imgur.com/Kwz01MX.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/Lk5KCKA.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

With the wireless module connected, navigate to the PC wireless section of the Laptop and connect to the Home Network.

<img src="https://i.imgur.com/51RDhsB.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Close the PC wireless tab and select the Web Browser. Within the web browser navigate to cisco.srv to verify the connectivity of the wireless network.

<img src="https://i.imgur.com/hfm4glc.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
