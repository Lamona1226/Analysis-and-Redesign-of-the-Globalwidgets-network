# Analysis-and-Redesign-of-the-Globalwidgets-network
DESIGN NETWORK AND CONFIGURATION
Design:
The corporate organization has geographically separated five offices. Each office communicates with
each other using frame relay. Each of them is considered to be an area to implement OSPF to route
the packets using the shortest path. The area specification is:
Area 1: Boston, Area 2: Mumbai, Area 3: Beijing, Area 4: London, Area 5: New York.
VLAN is used to separate departments within each location. This helps to subdivide a physical network
into individual broadcast domains. Each VLAN has PCs in a unique subnet. A router is needed to route
the packets from and to the specific VLAN.
The DHCP server in Boston assigns IP addresses for Boston and Mumbai. The DHCP server of Mumbai
assigns IP addresses for Beijing, London and New York. All locations have Technical and HR
departments. Boston and Mumbai have additional Finance departments.
# Documentation 
[ayman202467finalphase.pdf](https://github.com/user-attachments/files/18596978/ayman202467finalphase.pdf)
