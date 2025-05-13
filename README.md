# Wireshark for Beginners: Capture Packets

This project was completed as part of a guided Coursera project. It covers basic usage of Wireshark for network traffic analysis.

# Project Overview

This beginner-level project demonstrates how to:

- Install and configure Wireshark on Linux (Ubuntu).
- Capture packets on Ethernet interfaces.
- Apply display filters to isolate HTTPS traffic.
- Detect website visits using TLS handshakes.
- Filter out traffic from specific IP addresses.

# Key Skills

- Network Packet Capture
- Wireshark Filtering
- Basic Networking Concepts
- TCP/IP Protocol Analysis
- HTTPS and TLS Traffic Inspection

# Tools Used

- **Wireshark** – Network protocol analyzer
- **Ubuntu Linux** – OS used in the project environment
- **Coursera** – Guided project platform

Certification

This project is based on the **“Wireshark for Beginners: Capture Packets”** guided project by Coursera.

 # How to Use

If you'd like to replicate this:

1. Install Wireshark on Linux.
2. Run packet capture on your Ethernet interface.
3. Use filters like:
   - `tcp.port == 443`
   - `tls.handshake.type == 1`
   - `!(ip.addr == 8.43.85.97) and tcp.port == 443`

# Contact

Feel free to connect with me on https://www.linkedin.com/in/fatimamuhammad/ or check out more of my projects on my https://github.com/FatimaLearnsCyber
