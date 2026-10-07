# network-traffic-analysis

# Network Traffic Analysis Lab

**Author:** Shaik Altaaf  
**Focus:** Cybersecurity | Network Security | SOC  
**Tools:** Wireshark | Kali Linux | TCP/IP

---

## Overview

A hands-on network traffic analysis project conducted in a
Kali Linux virtual lab using Wireshark.

The project demonstrates practical analysis of ICMP, DNS,
TCP, UDP, HTTP, and HTTPS/TLS traffic.

## Objectives

- Analyze IP and ICMP communication
- Investigate DNS queries and responses
- Understand TCP connection establishment
- Analyze UDP communication
- Examine HTTP traffic over TCP port 80
- Examine HTTPS/TLS traffic over TCP port 443
- Apply OSI and TCP/IP networking concepts to real packets

## Environment

- Kali Linux
- Oracle VirtualBox
- Wireshark
- TCP/IP

## Tools

- Wireshark
- ping
- nslookup
- curl

## Methodology

1. Captured ICMP traffic using ping
2. Captured DNS traffic using nslookup
3. Analyzed the TCP three-way handshake
4. Analyzed UDP-based DNS communication
5. Captured HTTP traffic on port 80
6. Captured HTTPS/TLS traffic on port 443
7. Documented packet-level observations

## Findings

### 1. ICMP Analysis

- Source IP: `10.0.2.15`
- Destination IP: `8.8.8.8`
- Protocol: ICMP
- Traffic: Echo Request / Echo Reply

### 2. DNS Analysis

- Client IP: `10.0.2.15`
- DNS Server: `192.168.21.1`
- Protocol: UDP
- Destination Port: `53`
- Query: `example.com`

### 3. TCP Three-Way Handshake

- Client IP: `10.0.2.15`
- Client Port: `37258`
- Server IP: `104.20.23.154`
- Server Port: `443`

Observed:

```text
SYN → SYN-ACK → ACK
