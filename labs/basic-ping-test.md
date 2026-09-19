# Basic Ping Test

## Objective

To test basic network connectivity using the Windows `ping` command.

---

## Step 1: Open Command Prompt

Press:

Windows + R

Type:

cmd

Press Enter.

---

## Step 2: Test the Local Computer

Run:

ping 127.0.0.1

The address `127.0.0.1` is the IPv4 loopback address.

A successful response indicates that the local TCP/IP stack is responding.

---

## Step 3: Check the Default Gateway

First run:

ipconfig

Find the:

Default Gateway

Example:

Default Gateway: 192.168.1.1

Then test the gateway:

ping 192.168.1.1

Use the actual gateway address shown on your computer.

---

## Step 4: Test an External IP Address

Run:

ping 8.8.8.8

If responses are received, the computer can communicate with that IP address.

---

## Step 5: Test a Domain Name

Run:

ping example.com

This also tests whether the domain name can be resolved.

---

## Basic Troubleshooting Flow

127.0.0.1
    ↓
Default Gateway
    ↓
External IP Address
    ↓
Domain Name

Testing in stages can help identify where a connectivity problem may exist.

---

## Learning Outcome

After completing this lab, I can:

- Use the `ping` command
- Test the local TCP/IP stack
- Test a default gateway
- Test connectivity to an external IP
- Perform a basic network connectivity check
