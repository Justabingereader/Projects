# Network Packet Analysis Project

## Overview

Comprehensive packet analysis demonstrating network forensics, protocol analysis, and threat detection capabilities using Wireshark.

### Protocol Analysis

- **ICMP**: Echo request/reply analysis, fragmentation handling, TTL inspection
  
- **DNS**: Query/response tracking, A record resolution, proxy identification
  
- **ARP**: Request/reply cycles, MAC address resolution, cache behavior
  
- **IPv4**: Subnetting (/21 networks), fragmentation mechanics, MTU handling

### Network Forensics Techniques

- **Packet Filtering**: Created custom Wireshark filters for protocol isolation
  
- **Traffic Pattern Recognition**: Identified normal vs. anomalous network behavior
  
- **Frame Analysis**: Deep inspection of encapsulation layers (Ethernet → IP → ICMP)
  
- **I/O Graphing**: Visual traffic analysis for pattern detection

## Key Findings

### Network Traffic Analysis

- Analyzed 160+ fragmented packets with frame length 1514 bytes
  
- Identified successful ARP resolution with 33 ARP packets captured
  
- Tracked 8 ICMP packets (4 requests, 4 replies) indicating stable connectivity
  
- Detected DNS proxy behavior through TTL analysis (127 hops)

### Security Observations

**Potential Threats Identified:**

- ICMP tunneling vulnerabilities in unrestricted ping traffic
  
- ARP spoofing risks from unauthenticated broadcasts
  
- IP fragmentation attack vectors
  
- DNS cache exploitation possibilities

**Mitigation Recommendations:**

- Configure firewalls to block outbound pings to external endpoints
  
- Implement Dynamic ARP Inspection (DAI) on network switches
  
- Enable static ARP entries for critical infrastructure
  
- Monitor for abnormal fragmentation patterns

## Technical Environment

- **Tool**: Wireshark (packet capture and analysis)
  
- **Protocols**: ICMP, ARP, DNS, IPv4, IGMP
  
- **Network**: 172.18.9.0/21 subnet (255.255.248.0 mask)
  
- **Analysis Focus**: Internal network communication patterns


