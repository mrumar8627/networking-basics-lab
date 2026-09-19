# IP Address Basics

## What Is an IP Address?

An IP address is a logical address used to identify a device on a network.

A common IPv4 address looks like:

192.168.1.10

Devices on the same network normally need appropriate IP configuration to communicate with each other.

---

## IPv4 Address

IPv4 addresses consist of four numbers separated by dots.

Example:

192.168.1.10

Each number can range from 0 to 255.

---

## Example Network

Consider the following devices:

PC 1
IP Address: 192.168.1.10

PC 2
IP Address: 192.168.1.11

Router
IP Address: 192.168.1.1

These devices can be configured within the same basic network.

---

## Subnet Mask

A subnet mask helps determine which part of an IP address represents the network and which part represents the host.

A common subnet mask is:

255.255.255.0

This is also commonly written as:

/24

---

## Default Gateway

The default gateway is normally the device used to reach other networks.

In a small network, the router commonly acts as the default gateway.

Example:

Default Gateway: 192.168.1.1

---

## DNS

DNS stands for Domain Name System.

DNS helps translate domain names into IP addresses.

Example:

example.com
     ↓
IP Address

---

## DHCP

DHCP stands for Dynamic Host Configuration Protocol.

DHCP can automatically provide network configuration to devices.

It can provide:

- IP address
- Subnet mask
- Default gateway
- DNS server

---

## Checking IP Configuration in Windows

Use:

ipconfig

For detailed information:

ipconfig /all

---

## Key Learning Points

- An IP address identifies a device on a network.
- IPv4 uses four numbers separated by dots.
- A subnet mask defines network and host portions.
- A default gateway is used to reach other networks.
- DHCP can automatically provide network settings.
- DNS helps resolve domain names.

---

## Learning Note

Understanding IP addresses, subnet masks, gateways, DHCP, and DNS provides an important foundation for networking and system administration.
