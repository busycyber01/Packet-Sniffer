# Packet-Sniffer
## Demo

![Packet Sniffer Demo](screenshots/sniffer.png)

# Network Packet Sniffer

A Python tool that captures and analyzes live network traffic, displaying source/destination IPs, ports, and protocols in real time. Built as a cybersecurity learning project using Scapy.

## Features

- Captures live packets on a network interface
- Identifies TCP, UDP, and ICMP traffic
- Displays source/destination IP and port for each packet
- Optional BPF filtering (e.g. capture only web traffic)

## Requirements

- Python 3
- Scapy (`sudo apt install python3-scapy`)
- Root/sudo privileges (required for raw packet capture)

## How to Run

```bash
sudo python3 sniffer.py
```

Press `Ctrl+C` to stop capturing.

## Demo

![Packet Sniffer Demo](screenshots/sniffer.png)

## Example Output
Starting packet sniffer... Press Ctrl+C to stop.

[TCP] 192.168.1.42:51322 -> 142.250.180.14:443
[UDP] 192.168.1.42:53211 -> 8.8.8.8:53
[ICMP] 192.168.1.42 -> 8.8.8.8


## Author

Built by [busycyber0]
