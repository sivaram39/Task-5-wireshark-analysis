# Task 5 - Capture and Analyze Network Traffic Using Wireshark

## Overview

This project demonstrates basic network traffic analysis using **Wireshark**. Live network packets were captured, filtered, and analyzed to identify commonly used network protocols.

## Objective

- Capture live network traffic.
- Identify different network protocols.
- Analyze packet details using Wireshark.
- Export the captured traffic as a `.pcap` file.

## Tool Used

- Wireshark

## Steps Performed

1. Installed Wireshark.
2. Started packet capture on the active network interface.
3. Generated network traffic by browsing websites and using the `ping` command.
4. Captured packets for approximately one minute.
5. Stopped the packet capture.
6. Applied protocol filters.
7. Identified multiple network protocols.
8. Saved the capture as a `.pcap` file.

## Protocols Identified

### DNS (Domain Name System)
- Resolves domain names into IP addresses.
- Used whenever a website is accessed.

### TCP (Transmission Control Protocol)
- Provides reliable communication between network devices.
- Used for establishing and maintaining connections.

### TLS/HTTPS
- Encrypts communication between the client and web server.
- Ensures secure data transmission.

## Files Included

```
├── task5_capture.pcap
├── report.txt
└── README.md
```

## Learning Outcomes

- Learned how to capture live network traffic.
- Understood the structure of network packets.
- Identified common protocols such as DNS, TCP, and TLS.
- Gained practical experience using Wireshark filters for packet analysis.

## Conclusion

This task provided hands-on experience with packet capturing and protocol analysis using Wireshark. It improved understanding of how network communication works and how different protocols interact during normal internet usage.
