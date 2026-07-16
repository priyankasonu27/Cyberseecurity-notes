Nmap Commands Cheat Sheet

This repository contains basic Nmap commands that I practiced during my cybersecurity training.

Basic Scans
nmap <IP_Address>

Scans a single IP address.

nmap <domain.com>

Scans a single domain.

nmap domain1.com domain2.com domain3.com domain4.com

Scans multiple domains in a single command.

Host Discovery
nmap -sn <IP_Address>

Performs host discovery only (no port scan).

nmap -sn <domain.com>

Performs host discovery for a domain.

nmap <Network_IP>/24

Scans all hosts in a network.
Example:

nmap 192.168.1.0/24
nmap -sn <Network_IP>/24

Discovers live hosts on the network without scanning ports.

Operating System Detection
nmap -O <IP_Address or Domain>

Attempts to identify the target operating system.

Aggressive Scan
nmap -A <IP_Address or Domain>

Performs an aggressive scan including:

OS Detection
Version Detection
Script Scanning
Traceroute

UDP Scan
nmap -sU <IP_Address or Domain>

Scans UDP ports.

TCP Connect Scan
nmap -sT <IP_Address or Domain>

Performs a full TCP Connect Scan.

SYN Scan (Half-Open Scan)
nmap -sS <IP_Address or Domain>

Performs a TCP SYN Scan (Half-Open Scan).

ACK Scan
nmap -sA <IP_Address or Domain>

Performs an ACK Scan to analyze firewall rules.

Xmas Scan
nmap -sX <IP_Address or Domain>

Performs an Xmas Tree Scan to identify open and filtered ports.
