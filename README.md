This project demonstrates my ability to capture and analyze network traffic using Wireshark. It complements my offensive security lab by showing I can also understand traffic patterns from a defensive perspective.

## Environment
- Analyzer: Kali Linux (Wireshark)
- Target: Metasploitable 2 (192.168.56.101)
- Protocol Analyzed: ICMP (Ping)

## Methodology
1. Started packet capture on the host-only network interface (`eth1`).
2. Generated traffic by pinging the target machine (192.168.56.101).
3. Stopped the capture and filtered for ICMP packets.

## Key Findings
- Identified the structure of an ICMP Echo Request and Echo Reply.
- Confirmed communication between Kali (192.168.56.103) and Metasploitable (192.168.56.101).
- Analyzed the IP and ICMP headers to understand how network packets are structured.

## Conclusion
This project gave me hands-on experience with one of the most important tools used in a SOC (Security Operations Center). Understanding how packets travel across a network is essential for identifying malicious activity.
