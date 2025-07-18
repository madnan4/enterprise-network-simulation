\# Enterprise Network Simulation (Cisco Packet Tracer)

This project simulates a full enterprise network infrastructure using Cisco Packet Tracer, featuring:  
\- VLANs  
\- DHCP  
\- OSPF  
\- NAT  
\- Inter-VLAN Routing  
\- Multi-area OSPF  
\- Basic ISP simulation

\#\# 🧱 Network Topology

\!\[Network Topology\](topology.png)

\- \*\*Area 1 and Area 2\*\*: Each has 3 switches — 1 core switch and 2 access switches  
\- Each PC is connected to access switches, grouped into:  
  \- VLAN 10: Sales  
  \- VLAN 20: IT  
  \- VLAN 30: Marketing  
\- Each router performs inter-VLAN routing and DHCP  
\- NAT is configured at edge routers for internet access  
\- ISP router connects both branches via OSPF Area 0

\#\# 📁 Files

| File | Description |  
|------|-------------|  
| \`Area1.pkt\` | Cisco Packet Tracer file for Area 1 |  
| \`Area2.pkt\` | Cisco Packet Tracer file for Area 2 |  
| \`EnterpriseNetwork.pkt\` | Complete integrated topology |  
| \`topology.png\` | Network topology diagram |  
| \`enterprise network commands.pdf\`|CLI Commands for devices |

\#\# ⚙️ Technologies Used

\- \*\*Cisco Packet Tracer\*\*  
\- \*\*OSPF (Multi-Area)\*\*  
\- \*\*VLANs & Inter-VLAN Routing\*\*  
\- \*\*NAT Overload\*\*  
\- \*\*DHCP\*\*  
\- \*\*Access Control Lists (ACLs)\*\*

\#\# 🚀 How to Use

1\. Open \`.pkt\` files in Cisco Packet Tracer  
2\. View the topology and device configurations  
3\. Simulate ping, routing, DHCP, or NAT functionality  
4\. Modify or expand with security features (e.g., ACLs, Port Security)

\#\# 👨‍💻 Author

Adnan Mohammed Ali    
📫 \[LinkedIn\](https://www.linkedin.com/in/adnan-ali-0312b8251)

\---

\#\# 📌 Note

This project is part of a self-directed CCNA lab to demonstrate proficiency in enterprise networking, subnetting with VLSM, routing protocols, and Layer 2/3 design.

