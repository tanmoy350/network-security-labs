# Network Security Labs

A collection of hands-on cybersecurity and network security labs developed while building practical skills for Security Operations and Threat Detection roles.

## Objectives

- Understand network traffic and protocols
- Analyze packets using Wireshark
- Perform network reconnaissance using Nmap
- Investigate suspicious network activity
- Develop practical security analysis skills

## Tools

- Wireshark
- Nmap
- Linux
- Python
- TCP/IP networking

## Labs

### Wireshark
Packet capture and network traffic analysis exercises.

### Nmap
Network reconnaissance, port scanning, service discovery, and enumeration exercises.

### Networking
Practical exercises covering TCP/IP, DNS, HTTP/HTTPS, ports, protocols, and network behavior.

## Learning Approach

Each lab will document:

1. Objective
2. Environment
3. Procedure
4. Observations
5. Findings
6. Security relevance
7. Lessons learned


## Completed Labs

### 1. TCP Three-Way Handshake Analysis

**Tool:** Wireshark  
**Environment:** Windows 10, Loopback Interface

Analyzed TCP connection establishment by capturing and examining
the SYN, SYN-ACK, and ACK packets.

**Key observations:**
- Identified the TCP three-way handshake.
- Examined source and destination ports.
- Interpreted SYN and ACK flags.
- Observed sequence and acknowledgment numbers.
- Investigated traffic on the loopback interface.

**Evidence and report:**
[Read the practical report](wireshark/tcp-three-way-handshake/tcp-three-way-handshake.md)

**Status:** Completed

### 2. DNS Query and Response Analysis

**Tool:** Wireshark  
**Protocol:** DNS over UDP

Captured and analyzed DNS A and AAAA query-response exchanges for example.com.

**Key observations:**
- Identified DNS transaction IDs.
- Analyzed DNS query and response flags.
- Examined UDP source and destination ports.
- Identified NOERROR response codes.
- Investigated returned IPv4 and IPv6 records.

**Evidence and report:**
[Read the DNS analysis report](wireshark/DNS-Query-Response-Analysis/DNS-Query-Response-Analysis.md)

**Status:** Completed

## Upcoming Labs

- Nmap Network Service Discovery
- HTTP vs HTTPS Traffic Analysis
- Linux Authentication Log Investigation
