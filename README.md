
Project Overview:
ARP (Address Resolution Protocol) Spoofing is a type of Man-in-the-Middle (MITM) attack where an attacker sends fake ARP messages to a network, associating their MAC address with the IP address of another device (e.g., a router or a victim's system). This allows the attacker to intercept, modify, or disrupt network traffic.

Technical Implementation:
Attack Implementation:

Used Scapy (Python) to craft and send forged ARP packets.
Redirected traffic between a victim and the router, enabling eavesdropping.
Captured sensitive data such as login credentials using a packet sniffer (Wireshark/tcpdump).
Detection & Prevention:

Developed a Python-based ARP monitoring tool to detect anomalies.
Implemented real-time ARP table monitoring to check for MAC-IP mismatches.
Used Reverse ARP requests & static ARP entries to prevent spoofing attacks.
Integrated alerts and logging mechanisms for suspicious ARP activity.
Applications & Relevance:
Penetration Testing to assess network security.
Cybersecurity Defense by detecting malicious ARP spoofing attempts.
Network Security Research to improve real-time threat detection mechanisms.
