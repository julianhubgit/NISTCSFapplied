<h1>Use the NIST CSF Cybersecurity Framework to respond to a security incident</h1>


<h2>Description</h2>
A company experienced a security event when all network services suddenly
stopped responding. The cybersecurity team found the disruption was caused
by a distributed denial of services (DDoS) attack through a flood of incoming
ICMP packets. The team responded by blocking the attack and stopping all
non-critical network services, so that critical network services could be
restored. Using the <i>five</i> key components of the NIST CSF Framework outline how to respond effectively to this security incident.
<br />


<h2>Languages and Utilities Used</h2>

- <b>NIST CSF Cybersecurity Framework</b> 


<h1>Program walk-through:</h1>



<h2 align="center">Identify: </h2>
  
A flood of ICMP pings was sent through to our network through an unconfigured firewall. This flood of ICMP packets caused the network to stop responding as it overloaded the system’s bandwidth, not allowing the system to be able to forward traffic. This was a DDoS ICMP flood attack by the malicious actor. All critical network resources needed to be secured and restored to a functioning state.


<h2 align="center">Protect:</h2>

The team improved security by configuring the firewall to block ICMP pings from external sources. A VPN can be used to encrypt data and company IP address so data cannot be used by malicious actors and ICMP attacks in the future will be much more difficult as IP addresses will be encrypted. Also a new firewall rule was implemented to limit incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.


<h2 align="center">Detect:</h2>

The cybersecurity team configured source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and implemented network monitoring software to detect abnormal traffic patterns. The team also configured both an IDS and IPS system within the company’s infrastructure. And IDS would help detect and alert the company of any suspicious or malicious activity.

<h2 align="center">Respond:</h2>

Infected systems need to isolated to prevent further damage to the systems and network and then attempts will be made to restore critical systems affected. The team then implemented the use of network packet analyzers like tcpdump. These can be used to detect and identify malicious traffic, creating alerts for network issues or security threats. Data retrieved from a tcpdump, any other network packet analyzers and the IDS can let us know if any malicious actor has attempted to attack our network or systems. 

<h2 align="center">Recover:</h2>

In future cybersecurity incidents like this DDoS attack can be contained by blocking incoming ICMP packets from unknown external sources. This can be achieved by utilizing a configured firewall to block unknown external sources from sending ICMP packets. Affected devices can be contained by stopping all non-critical network services. Speedy response to the IDS can also help us minimise and contain the malicious attack. Systems must be analyzed to quantify the extent of the damage of the attack. Findings must be documented. 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
