# Wireshark Network Traffic Analysis

## Project Overview
This project demonstrates practical network packet analysis using Wireshark, completed as part of a cybersecurity internship. The task involved capturing live network traffic and analyzing different network protocols to understand how data is transmitted across networks.

## Task Objectives
- Capture live network packets using Wireshark
- Identify and analyze basic network protocols
- Understand the differences between TCP, UDP, and DNS protocols
- Generate a comprehensive analysis report

## 🛠️ Tools Used
- **Wireshark** - Network protocol analyzer
  
##  Analysis Summary

### Protocols Identified and Analyzed

#### 1. DNS (Domain Name System) - Packet #1
- **Purpose**: Domain name resolution
- **Key Details**:
  - Query for `teams.events.data.microsoft.com`
  - Source: `192.168.242.239:55302`
  - Destination: `192.168.242.94:53`
  - Uses UDP for fast, connectionless queries

#### 2. TCP (Transmission Control Protocol) - Packet #7
- **Purpose**: Reliable, connection-oriented data transfer
- **Key Details**:
  - HTTPS traffic (Port 443)
  - ACK packet maintaining connection state
  - Sequence number: 1, Acknowledgment number: 806
  - Demonstrates TCP's reliability features

#### 3. UDP (User Datagram Protocol) - Packet #2
- **Purpose**: Fast, connectionless data transport
- **Key Details**:
  - Carrying encrypted HTTPS traffic over QUIC protocol
  - Source port: 56190, Destination port: 443
  - 35-byte encrypted payload
  - Shows modern use of UDP for web traffic
## Key Learnings
- Practical understanding of network packet structure
- Differences between connection-oriented (TCP) and connectionless (UDP) protocols
- DNS resolution process and its importance in networking
- Modern protocol usage (QUIC over UDP for HTTPS)
- Wireshark filtering and analysis techniques
