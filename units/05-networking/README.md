# 05 · Networking, layer 2 to layer 7

**Priority:** High · **Effort:** ~3 week(s) · **Status:** not started

## Why this matters

Networking is where most outages and most attacks actually happen. Every layer makes an assumption about who sent a packet.

## 1. Stumble first (before any reading)

Run `tcpdump` and `curl -v https://example.com` at the same time. Before reading anything, write down every packet you expect to see, in order. Then compare with the capture.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Ethernet, MAC addresses, ARP, switching, VLANs
- [ ] How a Wi-Fi client discovers, joins and authenticates (802.11, WPA3, 802.1X)
- [ ] IP, subnetting, routing tables, NAT, DHCP
- [ ] TCP and UDP, the handshake, netfilter, nftables
- [ ] DNS, HTTP, TLS

## 3. Build yourself

A multi-subnet network in Linux namespaces with your own router, DHCP (dnsmasq), DNS and firewall, all watched in Wireshark.

## 4. Practise on

HTB Academy or TryHackMe networking modules.

## 5. Gate check

Trace one HTTPS request from DHCP lease to TLS session.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [Computer Networks: A Systems Approach (free)](https://book.systemsapproach.org/)
- [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/)
- [Wireshark documentation](https://www.wireshark.org/docs/)
- [Julia Evans zines (DNS, networking)](https://wizardzines.com/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.
