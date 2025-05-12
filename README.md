# Network Security Lab Setup
A beginner-friendly virtual lab to simulate network security, firewall configuration, and traffic control using pfSense, Ubuntu Server, and Kali Linux. Built using VirtualBox with a custom internal network.

# 📌 Project Summary
This project replicates a real-world enterprise network setup using:

pfSense as the firewall/router

Ubuntu Server as the target machine (web server)

Kali Linux as the attacker/client machine

All machines communicate within a VirtualBox internal network called LabNet, with statically assigned IPs.

# 🧱 Network Architecture
Kali Linux (Attacker/Client) → 192.168.100.10

pfSense (Firewall/Router) → 192.168.100.1

Ubuntu Server (Web Server) → 192.168.100.20

All devices are connected to LabNet (192.168.100.0/24)


# 🛠️ Tools & Technologies Used
VirtualBox

pfSense

Ubuntu Server (Apache2)

Kali Linux (nmap, curl, Wireshark)

Netplan & Bash (for static IP setup)

Custom firewall rules via pfSense Web UI

# ⚙️ Lab Setup Highlights
pfSense:
Installed on FreeBSD 64-bit VM

Configured with WAN (Bridged) + LAN (Internal)

LAN IP: 192.168.100.1

Ubuntu Server:
Static IP: 192.168.100.20

Apache2 installed to serve web content

Kali Linux:
Static IP: 192.168.100.10

Used for testing scans, ping, and curl requests

# ✅ Outcomes & Learning
Built a full functional network simulation for firewall testing

Practiced segmentation and traffic control

Understood rule ordering and pfSense logging

Gained hands-on experience in routing, port filtering, and basic web hosting

# Author
Prashant Jha | B.Tech CSE | Kalinga Institute of Industrial Technology (KIIT)
