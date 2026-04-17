#Traffic Classification System

##Problem Statement
This project captures live network traffic and classifies packets based on their protocol (TCP, UDP, ICMP, Others). It provides real-time insights into network behavior.

This aligns with SDN-based traffic observation and analysis requirements.


##Features
- Captures live packets using Scapy
- Classifies traffic into:
  - TCP
  - UDP
  - ICMP
  - OTHER
- Displays real-time packet logs
- Shows final statistics with percentages


##Requirements
- Python 3.x
- Scapy

Install dependency:
```bash
pip install scapy
