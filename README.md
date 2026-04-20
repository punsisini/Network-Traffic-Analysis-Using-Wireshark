# Network Traffic Analysis Using Wireshark (Ubuntu Lab)

## Overview
This project demonstrates a hands-on lab where I captured and analyzed network traffic using Wireshark in an Ubuntu virtual machine.

---

## Lab Environment
- VirtualBox
- Ubuntu VM
- NAT Network
- Wireshark
- curl

---

## Traffic Generation
- Browsing websites
- `ping google.com`
- `curl http://example.com`

---

## Analysis

### DNS Analysis
I observed how domain names are translated into IP addresses.

![DNS](dns.png)

---

### TCP Analysis
I analyzed TCP packets and observed the 3-way handshake (SYN, SYN-ACK, ACK).

![TCP](tcp.png)

---

### HTTP Analysis
Using curl, I captured HTTP traffic and observed readable request/response data.

![HTTP](http.png)

---

### Wireshark Capture Overview
General traffic capture showing multiple protocols.

![Wireshark](wireshark.png)

---

### Ubuntu Lab Environment
Ubuntu virtual machine used for analysis.

![Ubuntu](ubuntu.png)

---

## Key Learnings
- DNS resolution process
- TCP 3-way handshake
- HTTP vs HTTPS difference
- Packet filtering in Wireshark
- Basic network troubleshooting

---

## Conclusion
This project helped me understand real network traffic behavior and how tools like Wireshark are used in cybersecurity and network analysis.
