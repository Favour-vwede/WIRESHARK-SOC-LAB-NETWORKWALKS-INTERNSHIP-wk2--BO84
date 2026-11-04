
# 📡 Wireshark Network Traffic Analysis | Hands-on Labs

Exploring network traffic, capturing packets, and understanding how devices communicate through practical Wireshark exercises.

![Wireshark](https://img.shields.io/badge/Tool-Wireshark-1679A7)
![Focus](https://img.shields.io/badge/Focus-Network%20Analysis-blue)
![Domain](https://img.shields.io/badge/Domain-Cybersecurity-red)

## 📌 Project Overview

This repository documents my hands on practice with **Wireshark**, an open-source network protocol analyzer used to capture, inspect, and analyze network traffic.

As part of my cybersecurity learning journey, I have been working through practical exercises to understand how network communication happens at packet level.

The labs involve examining captured traffic, applying display filters, identifying protocols and ports, and interpreting packet information to better understand network behaviour.

The goal is to move beyond networking theory and develop practical skills in network traffic analysis.

## 🎯 Project Objectives

- Understand how network packets are captured and analyzed.
- Identify different network protocols and their functions.
- Examine TCP communication and connection establishment.
- Identify source and destination IP addresses.
- Understand TCP ports and their associated services.
- Apply Wireshark display filters to isolate specific traffic.
- Explore protocol hierarchy and network statistics.
- Develop confidence in interpreting packet-level information.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Wireshark | Network packet capture and analysis |
| Windows 11 | Host operating system |
| Labs | Lab 3 - Lab 8 |


## 🔬 Practical Labs & Exercises

The following are the major areas explored during my Wireshark practice sessions.

### 1. Packet Capture & Traffic Inspection

- Capturing live network traffic.
- Identifying active network interfaces.
- Examining captured packets.
- Understanding packet details and protocol layers.
- Observing communication between network devices.

###  LAB 3: IDENTIFY THE ATTACKERS IP

- Identifying source and destination IP addresses.
- ident
- Examining communication between devices.
- Understanding how packets travel across networks.
- Identifying hosts generating network traffic.
![identify the attackers ip](screenshots/traffic-capture.png)


### LAB 4: FOLLOW TCP STREAM 1

- Understanding the TCP three-way handshake.
- Identifying SYN, SYN-ACK, and ACK flags.
- Examining TCP connection behaviour.
- Identifying TCP ports in captured traffic.
- Understanding responses from closed ports.
![TCP Stream](screenshots/tcp-handshake.png)


### LAB 5: FOLLOW TCP STREAM 2

- Identifying protocols using packet details.
- Examining traffic on common ports such as 80, 443, and 22.
- Investigating traffic on unfamiliar TCP ports.
- Understanding how ports help identify network services.
![TCP Stream 2](screenshots/tcp-handshake.png)

### LAB 6: HTTP PLAIN TEXT CREDENTIALS

Practised using Wireshark display filters to narrow down packet captures and focus on specific traffic.

Some filters explored include:

| Display Filter | Purpose |
|---|---|
| `tcp` | Display TCP traffic |
| `udp` | Display UDP traffic |
| `dns` | Display DNS traffic |
| `http` | Display HTTP traffic |
| `ip.addr == x.x.x.x` | Filter traffic involving an IP |
| `tcp.port == 443` | Display traffic involving TCP port 443 |
| `tcp.flags.syn == 1` | Identify packets with the SYN flag set |
| `icmp` | Display ICMP traffic |
![Http](screenshots/tcp-handshake.png)
### LAB 7: CATCH THE BRUTE FORCE ATTACKER
Explored Wireshark's Statistics feature to understand the distribution of protocols within captured traffic.

Activities included:

- Using Protocol Hierarchy to identify protocols present in a capture.
- Examining the percentage of packets associated with different protocols.
- Identifying the protocols responsible for network communication.
- Using packet statistics to understand captured traffic.

### LAB 8: CATCH THE CALL SCAMMER

Explored how Wireshark's Follow TCP Stream feature helps examine communication between endpoints within a TCP connection.

This provided a better understanding of how individual packets form part of a larger communication session.

## 📊 Practical Skills Developed

Through these exercises, I have been developing practical skills in:

- Network packet capture.
- Network traffic inspection.
- TCP/IP analysis.
- Protocol identification.
- Port identification.
- IP address analysis.
- Wireshark display filtering.
- TCP flag interpretation.
- Network statistics and protocol hierarchy.
- Basic network troubleshooting.

## 📸 Lab Screenshots & Evidence

Screenshots from my practical sessions are included to document the exercises and demonstrate the analysis performed.

### 1. Network Traffic Capture

![Network Traffic Capture](screenshots/traffic-capture.png)

### 2. TCP Three-Way Handshake

![TCP Handshake](screenshots/tcp-handshake.png)

### 3. Display Filter Analysis

![Display Filters](screenshots/display-filters.png)

### 4. Protocol Hierarchy

![Protocol Hierarchy](screenshots/protocol-hierarchy.png)

### 5. TCP Port Analysis

![TCP Port Analysis](screenshots/tcp-port-analysis.png)

*Replace the example image paths with your actual screenshot filenames.*

## 💡 Key Learnings

Working through these labs has helped me understand networking concepts beyond what I initially learned in theory.

Some important takeaways include:

- Network communication becomes easier to understand when examined packet by packet.
- TCP flags provide useful information about connection establishment and communication.
- Ports help distinguish between different network services.
- Display filters make it easier to investigate specific traffic within large packet captures.
- Protocol Hierarchy provides a useful overview of the protocols present in a capture.
- Packet analysis requires observation, patience, and attention to detail.

## 🔮 Future Learning Goals

As I continue developing my cybersecurity skills, I intend to:

- Explore more advanced packet analysis.
- Practise identifying unusual network traffic patterns.
- Improve my understanding of network protocols.
- Explore DNS and HTTP/HTTPS traffic in greater detail.
- Build more practical network analysis projects.
- Connect packet analysis concepts to network security monitoring.

## 🔗 References & Learning Resources

- [Wireshark Official Website](https://www.wireshark.org/)
- [Wireshark User Guide](https://www.wireshark.org/docs/wsug_html/)
- [Wireshark Display Filters](https://wiki.wireshark.org/DisplayFilters)
- [Wireshark Documentation](https://www.wireshark.org/docs/)

## 👩‍💻 Author

**Favour**

Cybersecurity Learner | Aspiring Cybersecurity Professional

Currently building practical knowledge in cybersecurity, networking, Linux, and network traffic analysis.

---

*This repository documents my ongoing practical learning with Wireshark. It will continue to grow as I complete more exercises and develop my network analysis skills.*
