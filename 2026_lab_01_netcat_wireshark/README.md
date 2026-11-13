# Lab 01: Netcat + Wireshark

## Goal
Understand how plain-text network traffic looks on the wire by generating it with Netcat and inspecting it with Wireshark, then compare Nmap and Metasploit scanners against the same target.

## Setup
- Kali Linux (attacker) and Metasploitable 2 (target), both on a Host-only network.
- Verified connectivity with `ping`.

## Steps
1. **Netcat** (`01_netcat/notes.md`): listener/client chat, file transfer, banner grabbing.
2. **Wireshark** (`02_wireshark/`): capture the Netcat session, find the TCP 3-way handshake, use Follow TCP Stream, capture an Nmap scan.
3. **Metasploit** (`03_metasploit/notes.md`): `search`, `info`, `show options`, run an auxiliary scanner and compare with Nmap.
4. **Report** (`04_report/recon_report.md`): table of open services, versions, and observations.

## Key Takeaways
- (fill in) Why Netcat traffic is readable in Wireshark and what encryption changes.
- (fill in) Difference between an Nmap scan and a Metasploit auxiliary scanner.

## Tools
Netcat, Wireshark, Nmap, Metasploit Framework
