CORPORATE BUILDING NETWORK DESIGN

This project represents the network infrastructure design for a three-floor corporate building created using Cisco Packet Tracer. The aim of the project is to provide secure, scalable, and efficient communication between departments located on different floors while ensuring proper IP management, routing, and wireless connectivity.

The network is structured using a hierarchical topology:
Each floor acts as an individual network segment connected through access switches.
Multiple VLANs are configured to separate departments such as administration, development, support, and management, improving security and traffic control.
Inter-VLAN routing is implemented using routers to allow controlled communication between departments.
OSPF dynamic routing protocol is configured between backbone routers to ensure automatic path selection, redundancy, and efficient data forwarding across floors.
DHCP services are used to automatically assign IP addresses to PCs, laptops, smartphones, and printers within each VLAN, reducing manual configuration errors.
Wireless access points are deployed on every floor to provide connectivity for mobile devices.
SSH remote access is enabled on network devices to ensure secure device management instead of insecure protocols.

Key Objectives Achieved:

Logical segmentation using VLANs
Automatic IP allocation using DHCP
Dynamic routing with OSPF for inter-floor communication
Secure remote management via SSH
Wired and wireless connectivity for all users
Scalable and fault-tolerant backbone design

Conclusion:
This project demonstrates how a modern enterprise network can be designed to support multiple departments across floors with security, efficiency, and scalability. It reflects real-world corporate networking practices and provides a strong foundation for implementing advanced services such as firewalls, servers, and network monitoring in future expansions.
