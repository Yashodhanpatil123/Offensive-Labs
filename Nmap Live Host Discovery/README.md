<img width="1909" height="516" alt="image" src="https://github.com/user-attachments/assets/f3ec548a-73b6-46a1-9a83-59add25b00c5" />


---------

# TryHackMe




This room outlines the processes that Nmap takes before port-scanning to find which systems are online. This stage is critical since attempting to port-scan offline systems will merely waste time and create unneeded network noise (because it is active recon).

This room explains the steps Nmap takes to discover online systems before port scanning. This stage is crucial because attempting to port-scan offline systems will only waste time and generate unnecessary network noise.

We present the different approaches that Nmap uses to discover live hosts. In particular, we cover:

ARP scan: This scan uses ARP requests to discover live hosts
ICMP scan: This scan uses ICMP requests to identify live hosts
TCP/UDP ping scan: This scan sends packets to TCP ports and UDP ports to determine live hosts.
We also introduce two scanners, arp-scan and masscan, and explain how they overlap with part of Nmap’s host discovery.
