Enterprise Switch Configuration & Port Security

Implemented VLAN segmentation for SME network with best-practice security controls.
Network Design:

Engineering VLAN (VLAN 21): 192.168.21.0/24

Marketing VLAN (VLAN 22): 192.168.22.0/24

Accounts VLAN (VLAN 23): 192.168.23.0/24

Guest Radio VLAN (VLAN 24): 192.168.24.0/24


Security Implementation:

Port security with MAC address limits

Trunk/tagged connection configuration

Management VLAN isolation

Switchport security with violation policies

Static MAC address entries for spoofing prevention


Technical Analysis:

MAC address table behavior investigation

ARP aging timer configuration

Pre and post-VLAN network state comparison


Best Practices Applied:

Inactive port isolation to restricted VLANs

Username-based authentication control

Maximum port security threshold enforcement

Hardware: Cisco 2960-24TT Switches
