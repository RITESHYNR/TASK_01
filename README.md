Network-Port-Scanning
The Goal: To create a map of my local network (192.168.1.x) and identify which devices are active and what "doors" (ports) they have left open.

The Analogy: Think of the network as a street of houses.

IP Address: The house number.

Port: The doors and windows.

Port Scan: Knocking on every door to see which ones open.

How It Was Done I used a tool called Nmap on Windows. IPv4 Address. . . . . . . . . . . : 192.168.1.6 Subnet Mask . . . . . . . . . . . : 255.255.255.0

What it does: This sends a "SYN" packet (like a polite "Hello?") to every device on the network. If a device replies, we know it's there and listening.

Key Findings The scan found several devices with open ports.
