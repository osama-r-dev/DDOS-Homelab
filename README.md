# Objective

A hands-on cybersecurity lab focused on simulating and investigating Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) attack scenarios in a controlled environment.
The lab uses Windows 11, Kali Linux, pfSense, and Security Onion to simulate attack workflows involving ICMP, TCP/SYN, and HTTP traffic. Network activity is monitored and analyzed using tools such as Zeek and Wireshark, with Security Onion and Kibana used for security monitoring, log analysis, and visualization.

# 1 Prerequisites

## 1.1 Machines

- VirtualBox
- Kali Linux vm
- Windows vm
- pfSense
- Security onion

## 1.2 Tools

- hping3
- tmux
- Wireshark

# 2. Lab setup

## 2.1 Networking

### 2.1.1 Network toplogy

![Network Topology](/images/network_toplogy.jpg)

### 2.1.2 Subnets

| Name  | Machine     | IP           |
| ----- | ----------- | ------------ |
| Green | Wiondows 11 | 10.10.10.100 |
| Blue  | Value 5     | 10.10.20.100 |
| Red   | Value 2     | 10.10.30.100 |
| VPN   | Value 5     | 10.10.3.2    |

### 2.1.3 Firewall Rules

### Blue

![Network Topology](/images/Blue_rules.png)

### Green

![Network Topology](/images/Green_rules.png.png)

### Red

![Network Topology](/images/Red_Ruels.png)

### WAN

![Network Topology](/images/WAN_rules.png)
