# CCNA
Cisco certified  Network Associate
# 📡 CCNA Study Guide (README)

A complete, beginner‑friendly CCNA (Cisco Certified Network Associate) study guide — perfect for GitHub. This repository contains short notes, labs, commands, and resources to help you prepare effectively for the **CCNA 200‑301** certification.

---

## 📘 What is CCNA?

**CCNA (Cisco Certified Network Associate)** is an entry‑level networking certification that validates your ability to install, configure, operate, and troubleshoot small to medium-sized networks.

---

## 🎯 Learning Objectives

By completing this guide, you will learn:

* Network Fundamentals
* IP Addressing (IPv4 / IPv6)
* Routing & Switching Basics
* VLANs, Trunking, STP
* DHCP, NAT, ACLs
* Wireless Networking
* Network Security
* Automation & Programmability (Basics)

---

## 🗂️ Repository Structure

```
📁 ccna-study-guide
│── 📄 README.md
│── 📁 notes
│     ├── network_fundamentals.md
│     ├── ip_addressing.md
│     ├── routing_switching.md
│     ├── security.md
│     └── automation.md
│── 📁 labs
│     ├── basic_switch_config.txt
│     ├── vlan_lab.pkt
│     ├── routing_lab.pkt
│── 📁 commands
│     └── ccna_commands.md
│── 📁 resources
│     └── links.md
```

---

## 📝 CCNA Short Notes

### 🔹 Basic Switch Configuration

```
enable
configure terminal
hostname Switch1
no ip domain-lookup
service password-encryption
banner motd #Unauthorized access prohibited!#
enable secret cisco123
line console 0
 password cisco
 login
exit
```

### 🔹 Basic Router Configuration

```
configure terminal
hostname Router1
interface g0/0
 ip address 192.168.1.1 255.255.255.0
 no shutdown
exit
```

### 🔹 VLAN Configuration

```
configure terminal
vlan 10
 name SALES
vlan 20
 name HR
interface f0/1
 switchport mode access
 switchport access vlan 10
```

---

## 🧪 Packet Tracer Labs Included

* Basic Switch/Router Setup
* VLAN & Inter-VLAN Routing
* Static Routing / RIP / OSPF
* DHCP Configuration
* NAT (Static / Dynamic / PAT)
* ACL Configuration Labs

---

## 📚 Best Free Resources

* Cisco Official Learning Network
* Free CCNA course: **Cisco Skills For All**
* YouTube Channels:

  * Jeremy’s IT Lab
  * NetworkChuck
  * David Bombal
* Packet Tracer Download (Free for students)

---

## 💡 Tips for CCNA Exam

* Practice daily on Packet Tracer / GNS3
* Memorize subnetting (very important!)
* Revise commands daily
* Solve multiple CCNA practice tests

---

## 🤝 Contributions

Contributions are welcome! If you want to add more labs, notes, or resources, feel free to open a pull request.

---

## 📩 Contact

For doubts or collaboration:
**Email:** [yourmail@example.com](mailto:someshuphad@gmail.com)

---

### ⭐ If you find this helpful, don’t forget to star the repository!
