# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective  
Capture live network traffic and identify basic communication protocols using Wireshark.

## Tools Used  
- Wireshark – Free and open-source network protocol analyzer  
- Kali Linux – Operating System used for capturing packets

## Steps Performed

1. Launched Wireshark and selected the active network interface .
2. Started a live packet capture.
3. Generated traffic by:
   - Visiting a website (e.g., example.com)
   - Running network commands:
     bash
     ping google.com
     curl http://neverssl.com

4. Captured traffic for around **1 minute**.
5. Stopped the capture and began protocol filtering.
6. Applied filters in Wireshark to identify multiple protocols:
   - http for website requests
   - dns for domain name lookups
   - icmp for ping traffic
   - tcp for basic transport communication
7. Saved the full capture as a .pcap file.

## Protocols Observed in Capture

- DNS – Resolving domain names to IP addresses  
- ICMP – Ping requests/responses (e.g., to google.com)  
- HTTP – Website access using curl or browser  
- TCP – Underlying transport protocol used by many services

Each protocol was filtered and verified using Wireshark’s display filter bar.

## Output Files

- task5_packet_capture.pcap – Packet capture file
- screenshots/ 

## Outcome  
Successfully captured and analyzed live network traffic using Wireshark. Learned how to identify key protocols such as DNS, ICMP, HTTP, and TCP through real packet inspection and filtering.
