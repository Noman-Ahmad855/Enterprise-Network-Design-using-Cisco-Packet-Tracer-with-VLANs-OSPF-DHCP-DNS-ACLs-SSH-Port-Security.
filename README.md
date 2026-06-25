Enterprise Network with Redundancy Using Cisco Packet Tracer
--------------------------------------------------------------
--------------------------------------------------------------

Project Overview::

This project simulates a real-world enterprise network infrastructure using Cisco Packet Tracer. The network consists of a Main Office, Branch Office, and Backup Router to ensure high availability and fault tolerance.

The project demonstrates key networking concepts including VLAN segmentation, inter-VLAN routing, OSPF dynamic routing, DHCP, DNS, ACL security, SSH remote management, Port Security, and network redundancy.


Devices Used:

->3 Cisco Routers:

  . R1 (Main Router)
  . R2 (Backup Router)
  . R3 (Branch Router)

  ->6 Cisco Switches:
  .Core Switch
  . HR Switch
  . Finance Switch
  . IT Switch
  . Management Switch
  . Server Switch

  .DNS/DHCP Server

  .End User PCs
  
VLAN Configuration:
| VLAN ID | Department |
 10        HR         
 20        Finance    
 30        IT         
 40        Management 
 50        Servers    

Features Implemented:
VLAN Segmentation:
Departmental separation using VLANs to improve security and reduce broadcast traffic.

Inter-VLAN Routing:
Router-on-a-Stick configuration allows communication between VLANs.

OSPF Dynamic Routing:
OSPF is configured between routers for automatic route learning and failover.

DHCP:
Centralized DHCP service automatically assigns IP addresses to clients.

DNS:
DNS server resolves:

.[www.company.local](http://www.company.local)
.fileserver.company.local

ACL Security:
Finance department is restricted from accessing HR resources.

SSH:
Secure remote administration is enabled on routers.

Port Security:
Sticky MAC address learning is configured on access ports.

Password Encryption:
Passwords are encrypted using Cisco security features.

Redundancy:
Backup routing path ensures connectivity if the primary link fails.

Testing Performed:

. VLAN verification
. Inter-VLAN routing verification
. DHCP address assignment
. DNS resolution
. OSPF neighbor verification
. ACL functionality testing
. SSH remote login
.Port security verification
.Redundancy failover testing

 ->Technologies Used:

. Cisco Packet Tracer
. VLANs
. OSPF
. DHCP
. DNS
. ACLs
. SSH
. Port Security
. Password Encryption
