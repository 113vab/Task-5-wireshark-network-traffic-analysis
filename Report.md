# TASK 5 REPORT

# Capture and Analyze Network Traffic Using Wireshark

---

# 1. Introduction

Network traffic analysis is a fundamental cybersecurity practice used to monitor, inspect, and troubleshoot communication occurring between devices across a network. Every action performed on the internet—such as opening a website, sending an email, streaming a video, or downloading a file—generates network packets.

Wireshark is an open-source packet analyzer that enables security analysts, network engineers, and researchers to capture and inspect these packets in real time. It provides detailed visibility into network communications and helps identify protocol behavior, security issues, and troubleshooting information.

In this task, Wireshark was used to capture live network traffic generated through normal internet activity. Various protocol filters were applied to isolate specific traffic types and analyze their behavior.

---

# 2. Objective

The primary objectives of this task were:

* To install and configure Wireshark
* To capture live network traffic
* To observe packet-level communication
* To identify commonly used network protocols
* To understand how devices exchange information
* To analyze encrypted and unencrypted traffic
* To gain practical exposure to network monitoring tools

---

# 3. Tool Information

## Wireshark

Wireshark is a free and open-source network protocol analyzer used for:

* Network troubleshooting
* Security analysis
* Protocol development
* Educational purposes
* Performance monitoring

Features include:

* Real-time packet capture
* Deep packet inspection
* Protocol filtering
* Traffic analysis
* Exporting packet captures

Version Used: Wireshark 4.6.6

---

# 4. System Configuration

| Component        | Details          |
| ---------------- | ---------------- |
| Operating System | Windows 11       |
| Tool             | Wireshark        |
| Version          | 4.6.6            |
| Interface Used   | Wi-Fi Adapter    |
| Network Type     | Wireless Network |

---

# 5. Procedure

## Step 1: Install Wireshark

Wireshark was downloaded and installed successfully on the system. During installation, the required packet capture drivers were also installed.

---

## Step 2: Launch Wireshark

After installation, Wireshark was launched and available network interfaces were displayed.

The active Wi-Fi interface was selected because it showed live network activity.

---

## Step 3: Start Packet Capture

Packet capture was initiated on the selected interface.

At this stage Wireshark began recording all incoming and outgoing network packets.

---

## Step 4: Generate Network Traffic

To create network traffic:

* Websites were opened
* Search requests were performed
* Internet services were accessed

This generated various packet types that could be captured and analyzed.

---

## Step 5: Stop Capture

After collecting sufficient traffic, packet capture was stopped.

The captured packets remained available for further analysis.

---

## Step 6: Apply Protocol Filters

Wireshark display filters were used to isolate specific protocol traffic.

### DNS Filter

Filter Used:

dns

Purpose:

To display only Domain Name System traffic.

---

### TCP Filter

Filter Used:

tcp

Purpose:

To analyze Transmission Control Protocol packets.

---

### TLS Filter

Filter Used:

tls

Purpose:

To observe encrypted communication between client and server.

---

# 6. Analysis of Captured Protocols

## 6.1 DNS Analysis

### What is DNS?

DNS (Domain Name System) acts as the internet's phonebook.

Instead of remembering IP addresses, users enter domain names such as:

* google.com
* microsoft.com
* github.com

DNS converts these names into numerical IP addresses.

### Observations

The captured traffic showed:

* DNS Queries
* DNS Responses
* Domain Name Resolution
* IPv4 and IPv6 lookups

### Importance

Without DNS, users would need to remember numerical IP addresses for every website.

---

## 6.2 TCP Analysis

### What is TCP?

Transmission Control Protocol (TCP) is a connection-oriented protocol that ensures reliable communication.

TCP guarantees:

* Data delivery
* Correct packet order
* Error detection
* Retransmission of lost packets

### Observations

Captured packets showed:

* ACK packets
* TCP Retransmissions
* Session establishment
* Session termination

### Importance

TCP is widely used by:

* Web Browsers
* Email Services
* File Transfers
* Remote Access Services

---

## 6.3 TLS Analysis

### What is TLS?

Transport Layer Security (TLS) protects communications through encryption.

TLS ensures:

* Confidentiality
* Integrity
* Authentication

### Observations

The capture showed:

* TLS Client Hello
* TLS Server Hello
* Application Data
* Encrypted Traffic

### Importance

TLS protects sensitive information such as:

* Passwords
* Banking Transactions
* Personal Information
* Login Credentials

---

## 6.4 QUIC Analysis

### What is QUIC?

QUIC is a modern transport protocol developed to improve performance and security.

It combines:

* Transport Layer Functions
* Encryption
* Faster Connection Setup

### Observations

QUIC packets were detected during browsing activity.

### Importance

QUIC is widely used by:

* Google Services
* Modern Browsers
* Streaming Platforms

---

# 7. Results

The network traffic capture was successful.

Protocols identified include:

* DNS
* TCP
* TLS 1.2
* TLS 1.3
* QUIC

Thousands of packets were successfully captured and inspected.

The use of protocol filters allowed focused analysis of specific communication types.

---

# 8. Key Findings

* DNS traffic resolves domain names into IP addresses.
* TCP provides reliable communication.
* TLS encrypts sensitive network data.
* QUIC improves speed and security.
* Modern internet communication relies heavily on encryption.
* Packet analysis provides valuable insight into network behavior.

---

# 9. Learning Outcomes

After completing this task, I learned:

### Technical Skills

* Packet Capture
* Protocol Filtering
* Network Monitoring
* Traffic Analysis
* Basic Troubleshooting

### Networking Concepts

* DNS Resolution
* TCP Communication
* TLS Encryption
* QUIC Protocol
* Packet Structures

### Cybersecurity Concepts

* Network Visibility
* Traffic Inspection
* Secure Communications
* Monitoring Techniques

---

# 10. Conclusion

This task provided practical experience in capturing and analyzing network traffic using Wireshark. Different network protocols were successfully identified and studied, including DNS, TCP, TLS, and QUIC.

The exercise demonstrated how modern networks communicate, how secure connections are established, and how packet analyzers assist cybersecurity professionals in monitoring, troubleshooting, and securing network environments. The knowledge gained from this activity forms a strong foundation for further studies in networking and cybersecurity.
