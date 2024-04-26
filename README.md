# Network Attack and Defence Project Report

This repository contains the project report for the Network Attack and Defence coursework as part of the Network Security module. The report covers the various stages of the project, including building a network, generating and analyzing traffic, conducting network attacks, and implementing defence mechanisms.

## Table of Contents
1. [Level 1: Build a network and test its connectivity](#level-1-build-a-network-and-test-its-connectivity)
   - [Network Topology](#network-topology)
   - [Connectivity Tests](#connectivity-tests)
2. [Level 2: Generate and analyse traffic on your network](#level-2-generate-and-analyse-traffic-on-your-network)
   - [Protocol Analysis](#protocol-analysis)
   - [Packet Analysis](#packet-analysis)
   - [Flow Analysis](#flow-analysis)
   - [Performance Analysis](#performance-analysis)
3. [Level 3: Network attacks](#level-3-network-attacks)
   - [TCP SYN Flood Attack with IP Spoofing](#tcp-syn-flood-attack-with-ip-spoofing)
   - [ICMP Flood Attack](#icmp-flood-attack)
   - [Packet Analysis](#packet-analysis-1)
   - [Flow Analysis](#flow-analysis-1)
4. [Level 4: Network defence](#level-4-network-defence)
   - [Firewall Configuration](#firewall-configuration)
     - [TCP SYN Flood Attack with IP Spoofing](#tcp-syn-flood-attack-with-ip-spoofing-1)
     - [ICMP Flood Attack](#icmp-flood-attack-1)
   - [Dropped Packets](#dropped-packets)
   - [Performance Metrics](#performance-metrics)
5. [Level 5: Critical evaluation and reflection](#level-5-critical-evaluation-and-reflection)

## Authors
- Ahmed Bedair
- Yukesh Shrestha
- Varishdan Kumariah

## Tools Used
- Wireshark
- iperf
- hping3
- iptables

## Key Findings
- Successfully built a network topology consisting of an attacker machine and two victim machines
- Generated and analyzed network traffic using iperf and Wireshark
- Conducted TCP SYN Flood and ICMP Flood attacks to demonstrate the impact on the network
- Implemented iptables firewall rules on the victim machines to mitigate the effects of the attacks
- Maintained stable network performance despite the attacks by fine-tuning the firewall configuration

For a detailed analysis and discussion of each stage of the project, please refer to the full report in the [main.pdf](main.pdf) file.