Packet Sniffer

Overview

This Packet Sniffer is a network security tool that captures and analyzes raw network packets. It extracts Ethernet frame details, including source and destination MAC addresses.

Features

Captures packets in real-time

Extracts Ethernet frame details (MAC addresses, protocol type)

Can be extended to parse IP, TCP, UDP headers

Prerequisites

Python 3.x

Run the script with root/administrator privileges (required for raw socket access)

Installation

# Clone the repository
git clone https://github.com/yourusername/Packet-Sniffer.git
cd Packet-Sniffer

# Install dependencies (if any, currently none)
pip install -r requirements.txt

Usage

sudo python3 src/packet_sniffer.py

Notes

The script currently works on Linux. For Windows, consider using a library like scapy or winpcap.

License

This project is licensed under the MIT License.

