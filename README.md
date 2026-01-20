# SYN-Flood-Report
TCP SYN flood incident analysis using TCP/HTTP logs to identify DoS behavior.

## Objective
Demonstrate the identification and analysis of a SYN flood attack, showing how it impacts server availability and TCP handshake processing.

## Approach
- Collected TCP/HTTP logs from Wireshark
- Identified abnormal SYN packet patterns
- Explained the TCP three-way handshake and how it is exploited in a SYN flood
- Documented findings with supporting images and spreadsheets

## Findings
The attack originated from IP 203.0.113.0, causing a saturation of half-open TCP connections. Legitimate traffic was blocked, resulting in temporary denial of service.

## Files
- syn_flood.html → Full incident report page
- style.css → CSS used for formatting
