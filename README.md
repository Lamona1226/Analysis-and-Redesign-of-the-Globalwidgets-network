# Analysis and Redesign of the GlobalWidgets Network
📌 Project Overview

This project focuses on analyzing and redesigning the GlobalWidgets corporate network, which consists of five geographically separated offices. The redesign aims to improve network efficiency, ensure scalability, and optimize routing using OSPF (Open Shortest Path First) and VLANs (Virtual Local Area Networks).
🌍 Network Design & Configuration
1️⃣ Network Structure

    The corporate network consists of five geographically distributed offices:
        Area 1: Boston
        Area 2: Mumbai
        Area 3: Beijing
        Area 4: London
        Area 5: New York
    Each office communicates via Frame Relay, ensuring efficient wide-area network (WAN) connectivity.
    Each office is designated as an OSPF area, allowing optimized packet routing using the shortest path.

2️⃣ VLAN Implementation

    VLANs are used to segment departments within each office, reducing network congestion and improving security.
    Each VLAN corresponds to a unique subnet, ensuring logical separation of network traffic.
    Router-on-a-stick configuration is used, where a router connects different VLANs and facilitates inter-VLAN communication.

3️⃣ DHCP Configuration

    Dynamic Host Configuration Protocol (DHCP) is used for automatic IP address assignment.
    Boston's DHCP server assigns IP addresses for Boston and Mumbai.
    Mumbai's DHCP server assigns IP addresses for Beijing, London, and New York.

4️⃣ Department Structure & IP Allocation

Each office includes the following departments:
✅ Technical
✅ HR
✅ Finance (Only in Boston and Mumbai)
🔍 Routing & Communication

    OSPF is implemented for dynamic routing, ensuring packets are forwarded along the most efficient path.
    Inter-VLAN routing is handled by a layer 3 device (router or L3 switch) to enable communication between different VLANs.
    Frame Relay provides cost-effective and scalable WAN connectivity between global locations.

🛠 Key Benefits of the Redesigned Network

🚀 Improved Performance: Shortest path routing with OSPF minimizes latency.
🔒 Enhanced Security: VLANs isolate departments, reducing broadcast traffic.
📡 Scalability: Frame Relay WAN allows easy expansion of the network.
⚡ Efficient IP Management: DHCP dynamically assigns addresses, reducing manual configurations.
📊 Future Enhancements

    Implement QoS (Quality of Service) for better bandwidth management.
    Deploy redundant links to improve fault tolerance.
    Transition to MPLS for enhanced WAN performance.
# Documentation 
[ayman202467finalphase.pdf](https://github.com/user-attachments/files/18596978/ayman202467finalphase.pdf)
