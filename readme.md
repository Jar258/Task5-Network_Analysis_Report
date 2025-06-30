Task 5 - Network Traffic Analysis with Wireshark
Overview
This repository contains the submission for *Task 5* of the network analysis module. The task involved capturing and analyzing different types of network traffic using *Wireshark*, including:
*TCP (Transmission Control Protocol)*
*ICMPv6 (Internet Control Message Protocol version 6)*
*mdns (Multicast DNS)*
The objective was to study the characteristics of each protocol, identify packet flows, and understand network communication patterns.

File Name                               Description                                                              
 `Task5_Network_Analysis_Report.docx`   Detailed report analyzing captured TCP, ICMPv6, and mDNS traffic.         
 `README.md`                            Description of the task and files included in this repository.            
 `Wireshark_Screenshots/`               Folder containing screenshots of the filtered Wireshark captures.         

 Analysis Summary

TCP
- Observed a 3-way handshake.
- Analyzed TCP re-transmissions and handshake sequences.
- Identified TLS 1.2 handshake initiation (Client Hello, Server Hello).

ICMPv6
- Captured Neighbor Solicitation and Multicast Listener Report messages.
- Confirmed IPv6 address resolution activities.

mdns
- Captured mDNS queries and responses to `_googlecast._tcp.local`, `_ipp._tcp.local`, etc.
- Observed service discovery on a local network.

How to Use

1. Open the `.docx` report file to review the detailed analysis.
2. Review screenshots in the `Wireshark_Screenshots` folder for visual verification of findings.
3. Optionally, use Wireshark to replicate the analysis using similar filters:
   - `tcp`
   - `icmpv6`
   - `mdns`

---

Tools Used

*Wireshark v4.2.x*
*Windows 10 / 11 Environment*
*Microsoft Word / LibreOffice Writer for documentation*


📧 Shiv Raj 
📅 Date: 30 June 2025
