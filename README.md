# Company_Network_Scheme

**Cisco Packet Tracer Project**

The scheme was developed for the company. Each department is assigned a separate VLAN. 
In internal networks, use one external IP address 210.214.1.2 to connect to the Internet. 
The routers implement access control lists (ACLs) to protect networks.
The routers provide optimal route exchange using OSPF.

Two servers are added:
1.	DHCP-SYSLOG server:
Assigns IP addresses and other network parameters to devices.
Stores log files from devices via the SYSLOG protocol.
Only the IT department has full access to the server (VLAN 7).
UDP traffic to port 514 for SYSLOG from all devices and traffic to ports 67 and 68 used for DHCP is allowed. Other traffic to the DHCP server is denied.
2.	File server:
Used to store the files of the finance and accounting departments.
Only the accounting and finance departments (VLAN 3 and VLAN 5) have access to the server via SMB (Server Message Block) protocol on port 445.


**Implemented Technologies**

- Creation of network topology using Cisco Packet Tracer.
- Application of Hierarchical Network Design principles.
- Proper cabling connections for networking devices.
- Configuration of basic device settings.
- Establishment of VLANs and assignment of VLAN numbers to ports.
- Execution of subnetting and IP addressing.
- Setup of Inter-VLAN Routing on multilayer switches using Switch Virtual Interface (SVI).
- Implementation of a dedicated DHCP server for dynamic IP address allocation.
- Setup of SSH for secure remote access.
- Configuration of OSPF as the routing protocol.
- Implementation of NAT Overload (Port Address Translation, PAT).
- Configuration of standard and extended Access Control Lists (ACL).
- Enforcement of switchport security (Port-Security) on switches.
- Deployment of WLAN (Cisco Access Point).
- Configuration of host devices.
- Setup and configuration of ISP routers.
- Testing and verification of network communication.


  
