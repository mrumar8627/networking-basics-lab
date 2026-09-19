# DHCP

## What Is DHCP?

DHCP stands for **Dynamic Host Configuration Protocol**.

DHCP automatically provides network configuration to devices.

Instead of manually entering network settings on every computer, a DHCP server can assign them automatically.

---

## DHCP Can Provide

A DHCP server can provide:

- IP address
- Subnet mask
- Default gateway
- DNS server

---

## Example

When a computer connects to a network, a DHCP server may provide:

IP Address:      192.168.1.20
Subnet Mask:     255.255.255.0
Default Gateway: 192.168.1.1
DNS Server:      192.168.1.1

---

## Why DHCP Is Useful

DHCP makes network configuration easier, especially when many devices are connected to a network.

For example, a school computer lab may contain many computers. DHCP can automatically provide network settings instead of configuring each computer manually.

---

## DHCP and Static IP

There are two common ways to configure an IP address:

### DHCP

The device receives its network configuration automatically.

### Static IP

The network configuration is entered manually.

Static IP addresses are commonly useful for certain devices such as servers, printers, and network infrastructure.

---

## Checking DHCP Information

In Windows, use:

ipconfig /all

Look for:

DHCP Enabled
DHCP Server

---

## Learning Note

DHCP is an important network service that simplifies IP configuration in local networks.
