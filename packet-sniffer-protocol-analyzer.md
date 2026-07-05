# packet-sniffer-protocol-analyzer
A Python-based packet sniffer built with Scapy that captures live network traffic and displays source IP, destination IP, protocol, and packet length for real-time packet analysis.
---

## Features

- Captures live network packets
- Displays Source IP Address
- Displays Destination IP Address
- Identifies network protocols (TCP, UDP, ICMP)
- Displays packet length
- Simple and beginner-friendly packet analysis tool

---

## Technologies Used

- Python 3
- Scapy
- Networking (TCP/IP)

---

## Project Structure

```
Packet-Sniffer-Protocol-Analyzer/
│
├── packet_sniffer.py
├── README.md
├── requirements.txt
└── screenshots/
```

---

## How It Works

1. Starts the packet sniffer.
2. Captures live network packets.
3. Checks whether the packet contains an IP layer.
4. Extracts:
   - Source IP Address
   - Destination IP Address
   - Network Protocol
   - Packet Length
5. Displays the captured packet information in the terminal.

---

## Sample Output

```
Packet Sniffer Started...

Packet Captured

Source IP      : 192.168.1.5

Destination IP : 8.8.4.4

Protocol       : UDP

Packet Length  : 1292 Bytes

------------------------------------
```

---

## Skills Demonstrated

- Python Programming
- Network Packet Analysis
- TCP/IP Fundamentals
- Protocol Identification
- Scapy Library
- Basic Cybersecurity Monitoring

---

## Learning Outcomes

Through this project, I learned:

- How network packets are captured
- How to use Scapy for packet sniffing
- How to extract IP addresses from packets
- How to identify TCP, UDP, and ICMP protocols
- How packet length varies based on network traffic
- Basic concepts of network monitoring

---

## Future Improvements

- Save captured packets to CSV
- Add protocol statistics
- Detect suspicious ports
- Display source and destination ports
- Export packets to PCAP format
- Build a graphical dashboard

---
https://github.com/sakthi6145
