# SmallSpooferDetector
# ARP Spoofing Detection Tool (Python)

## Overview
This Python script is a **real-time ARP spoofing detection tool** designed to monitor your local network and alert you if a potential ARP-based man-in-the-middle (MITM) attack is detected. It is built using the **Scapy** library and focuses on identifying mismatches between the actual MAC addresses of devices and the MAC addresses reported in ARP responses.

> ⚠️ **Important:** This script is intended for educational purposes and monitoring networks you own or have explicit permission to test. Running this on unauthorized networks is illegal.

---

## Features

- **ARP Spoof Detection:** Continuously monitors ARP responses on the network and detects when a device is impersonated.
- **MAC Address Verification:** Compares the actual MAC address of a device with the MAC address reported in ARP replies.
- **Real-Time Alerts:** Prints alerts to the console if a device is under attack or confirms network safety.
- **Packet Inspection:** Displays details of ARP packets for further analysis.

---

## Requirements

- Python 3.x
- Linux or Windows OS
- Python library: `scapy`

Install Scapy using:

```bash
pip install scapy
