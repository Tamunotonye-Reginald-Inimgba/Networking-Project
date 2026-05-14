# Networking-Project
Hands‑on networking labs built in Cisco Packet Tracer, covering subnetting, routing, ACLs and basic network security.
## Databridge Network Segmentation & ACL Lab

[📄 View full lab report (PDF)]([Databrbridge_Networking_Project_Report.pdf](https://drive.google.com/file/d/1bBDjMx5JDcj5ElkOj2KxkUnfaoTEbrrK/view?usp=sharing))

### Overview
This lab simulates a small enterprise network in Cisco Packet Tracer using a core router named **Databridge**. The network is segmented into HR, Sales and Admin subnets, with routing and extended Access Control Lists (ACLs) used to enforce security policies between departments. Connectivity is verified with ICMP pings before and after the ACL is applied to show the impact of the configuration.

### Tools & Technologies
- Cisco Packet Tracer (topology design, router/switch configuration)
- Windows command line (ping/connectivity testing)
- IPv4 subnetting and default gateway configuration
- Cisco IOS CLI (extended ACL configuration)

### Key Lab Highlights
- Designed a routed, multi‑subnet topology connecting HR, Sales and Admin networks via the **Databridge** router.
- Implemented an **extended ACL (HR-ACL)** to block HR (192.168.30.0/24) from reaching Admin servers (192.168.10.0/24) while allowing HR ↔ Sales traffic.
- Captured **baseline pings** showing full reachability before the ACL and **post‑ACL pings** showing “Destination host unreachable” from HR to Admin.
- Demonstrated good practice: baseline testing → configuration changes → targeted validation and documentation in a structured lab report.
