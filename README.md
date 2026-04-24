# Network Traffic Analysis using Wireshark

## Objective

The goal of this project is to capture and analyze real network traffic to understand how devices communicate over a network.

## Tools Used

* Wireshark (network protocol analyzer)

## Methodology

1. Installed Wireshark and captured live network traffic
2. Generated traffic by browsing websites and streaming content
3. Applied filters to isolate specific protocols:

   * DNS
   * TCP
   * TLS

## Analysis & Findings

### DNS Analysis

DNS (Domain Name System) translates domain names into IP addresses.

* Observed DNS queries to:

  * google.com
  * youtube.com
  * activision.com
  * instagram.com
  * discord.com
  * battle.net
* This shows how my system locates servers on the internet.

### TCP Analysis

TCP (Transmission Control Protocol) is responsible for establishing reliable connections.

* Observed TCP handshakes between my device and external servers
* Ensures data is delivered correctly

### TLS Analysis

TLS (Transport Layer Security) encrypts data during transmission.

* Observed encrypted traffic when accessing secure websites
* Prevents attackers from reading sensitive data

## Screenshots

* See media

## Conclusion

This project demonstrates how network traffic can be captured and analyzed using Wireshark. It highlights the importance of DNS, TCP, and TLS in everyday internet communication and security.

## Skills Gained

* Network traffic analysis
* Understanding of core protocols (DNS, TCP, TLS)
* Basic cybersecurity analysis skills.
