# 💼 Networking Portfolio — Akashdeep Singh

## 👨‍💻 About Me
Computer Systems Networking graduate with hands-on experience building and troubleshooting network environments. Skilled in configuring VLANs, routing, IP addressing, and diagnosing connectivity issues through real-world lab simulations. Passionate about IT infrastructure, problem-solving, and continuous learning.

---

## 🛠 Technical Skills

**Networking**
- TCP/IP
- VLAN Configuration
- Routing & Switching
- Subnetting
- Network Troubleshooting

**Systems**
- Windows OS
- Basic Linux Administration
- Hardware Setup & Diagnostics

**Tools**
- Cisco Packet Tracer
- GitHub
- Command Line (CLI)

---

## 📂 Projects
### 🔹 Help Desk Troubleshooting Simulation
🏢 Segmented Helpdesk Network (Cisco Packet Tracer)
📌 Project Summary

Designed and implemented a small enterprise-style office network with a centralized Helpdesk web service.
The network is segmented using VLANs and secured with access control policies to separate Employees, IT Support, Guests, and Servers.

This project demonstrates practical networking, security, and troubleshooting skills using Cisco Packet Tracer.

🧱 Network Design

The network includes:

Router-on-a-Stick for inter-VLAN routing

Layer-2 switch with multiple VLANs

Internal DNS and HTTP server

Employee, IT, and Guest user networks

🗂 VLAN Architecture
VLAN	Role	Subnet
10	Employee	192.168.10.0/24
20	IT Support	192.168.20.0/24
30	Guest	192.168.30.0/24
50	Server	192.168.50.0/24

VLAN segmentation improves security and limits unnecessary network access between departments.

🌐 Core Services

DHCP: Centralized IP assignment for all VLANs

DNS: Internal name resolution (helpdesk.local)

HTTP: Internal Helpdesk web portal hosted on the server

Employees and IT staff can access the helpdesk portal using a domain name instead of an IP address.

🔐 Security Controls

An ACL was implemented to block Guest VLAN access to the Server VLAN while allowing internal users to reach business services.

This simulates real-world guest network isolation commonly used in enterprise environments.

🛠 Troubleshooting Scenario

A simulated DNS failure was introduced by removing the DNS record for the helpdesk portal.

Diagnosis:

Server reachable by IP

Web service running

Name resolution failed

Resolution:
The DNS record was restored, immediately recovering access.

🧠 Skills Demonstrated

VLAN configuration and segmentation

Inter-VLAN routing (Router-on-a-Stick)

DHCP and DNS services

Web server hosting

ACL-based security

Network troubleshooting and root-cause analysis

🔚 Conclusion

This project demonstrates the ability to design, secure, and troubleshoot a segmented enterprise network while supporting internal business services.
The lab reflects real-world scenarios relevant to IT Support, NOC, and Junior Network Administrator roles.



---

## 🎯 Objective
Seeking an entry-level IT / Networking / Help Desk position where I can apply technical knowledge, grow professionally, and contribute to real-world infrastructure environments.

---

## 📫 Contact
- Email: your@email.com
- LinkedIn: https://linkedin.com/in/yourprofile
- Portfolio Website: https://yourusername.github.io

---

## ⭐ Notes for Recruiters
This portfolio demonstrates practical technical ability through real configuration labs and simulations, not just theoretical knowledge.
