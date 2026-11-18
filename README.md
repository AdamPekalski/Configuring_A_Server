# CMPU 4050 Assignment 2

Integrated Linux server configuration.

## Domain

student75872.lan

## Required Services

- BIND9 DNS
- ISC DHCP Server
- NFS
- vsftpd
- Routing and NAT

## Network Plan

Server internal address: `192.168.1.1/24`

DHCP client range:

`192.168.1.150 - 192.168.1.200`

The server will act as the DNS server and default gateway for DHCP clients.
