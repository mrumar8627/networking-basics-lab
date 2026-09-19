# IPConfig Lab

## Objective

To inspect the network configuration of a Windows computer using the `ipconfig` command.

---

## Step 1: Open Command Prompt

Open Command Prompt and run:

ipconfig

---

## Step 2: Check the Network Information

Look for:

- IPv4 Address
- Subnet Mask
- Default Gateway

Example:

IPv4 Address:     192.168.1.20
Subnet Mask:      255.255.255.0
Default Gateway:  192.168.1.1

---

## Step 3: View Detailed Information

Run:

ipconfig /all

This provides additional information such as:

- MAC address
- DHCP status
- DHCP server
- DNS servers
- Network adapter information

---

## Step 4: Record the Results

Example:

IPv4 Address: 192.168.1.20
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1
DHCP Enabled: Yes

Do not publish real personal or sensitive network information from a real network.

---

## Step 5: Test Connectivity

After checking the configuration, test the default gateway:

ping 192.168.1.1

Replace the example address with the actual gateway shown by `ipconfig`.

---

## Learning Outcome

After completing this lab, I can:

- Check a Windows computer's IP configuration
- Identify an IPv4 address
- Identify a subnet mask
- Identify the default gateway
- Check DHCP information
- Perform a basic connectivity test
