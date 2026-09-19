# Basic Network Troubleshooting

## Objective

To follow a structured process when troubleshooting a basic network connectivity problem.

---

## Step 1: Check Physical Connections

Check:

- Network cable
- Router
- Switch
- Power
- Network adapter
- Wi-Fi connection

---

## Step 2: Check the Network Adapter

Make sure the network adapter is enabled.

In Windows, network adapter information can be checked through:

- Settings
- Network Connections
- Device Manager

---

## Step 3: Check IP Configuration

Run:

ipconfig

Check:

- IPv4 address
- Subnet mask
- Default gateway

For detailed information:

ipconfig /all

---

## Step 4: Test the Local Computer

Run:

ping 127.0.0.1

This checks the local TCP/IP stack.

---

## Step 5: Test the Default Gateway

Find the default gateway using:

ipconfig

Then test it:

ping <gateway-ip>

Example:

ping 192.168.1.1

---

## Step 6: Test an External IP Address

Try:

ping 8.8.8.8

This can help determine whether communication beyond the local network is working.

---

## Step 7: Check DNS

Try:

nslookup example.com

If IP connectivity works but domain-name resolution fails, DNS may be one possible cause.

---

## Troubleshooting Flow

Physical Connection
        ↓
Network Adapter
        ↓
IP Configuration
        ↓
Local TCP/IP
        ↓
Default Gateway
        ↓
External Connectivity
        ↓
DNS

---

## Documentation

When troubleshooting an issue, record:

### Problem

What is the user experiencing?

### Checks Performed

What did you test?

### Findings

What did you discover?

### Solution

What fixed the problem?

### Result

Was the problem resolved?

---

## Learning Note

A structured troubleshooting process helps avoid random changes and makes it easier to identify the possible cause of a network problem.

This repository focuses on beginner-level networking knowledge as part of my preparation for an **Ausbildung als Fachinformatiker für Systemintegration** in Germany.
