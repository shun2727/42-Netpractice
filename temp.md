
- **Subnet** vs **VLAN** : A VLAN and a subnet both divide a large computer network into smaller, manageable sections to improve security and performance. However : 
	- **Subnet** : A subnet is a Layer 3 concept
	- **VLAN** : A VLAN is a virtual LAN, and a LAN is a subnetwork, a.k.a. a subnet. It's a layer 2 (data link layer) concept. 
	- A **Virtual Interface** (SVI, Sub Interface, aka Vlan interface, etc.) is generally accepted as a coupling of the 2 concepts. Pairing a subnet (layer3) to a virtual interface, and assigning it a vlan (layer 2). T

	_source : https://www.geeksforgeeks.org/computer-networks/difference-between-vlan-and-subnet/_

	_source for TCP/IP addressing : https://www.ibm.com/docs/en/aix/7.2.0?topic=protocol-tcpip-addressing_

	#### Additional infomartion 
1. In order to allow internal IP addresses to connect to external network. Routers carry out NAT (network addresss translation). There are several types of NAT :
	-  Static : 1 private is mapped to 1 public address
	- PAT Pool : Multiple private addresses can be connected to a pool of public addresses
	- PAT Overloading : Many private ip addresses uses 1 public IP