# DNS

## What Is DNS?

DNS stands for **Domain Name System**.

DNS translates human-readable domain names into IP addresses.

For example:

example.com
     ↓
IP Address

---

## Why Is DNS Needed?

People can remember domain names more easily than IP addresses.

Instead of entering an IP address, users can enter a domain name such as:

example.com

DNS helps find the IP address associated with the domain.

---

## DNS Example

When a user enters a website address:

www.example.com

The computer can use DNS to find the corresponding IP address.

The computer can then communicate with the destination server.

---

## Basic DNS Test

Windows provides the `nslookup` command.

Example:

nslookup example.com

This command can display information about the DNS lookup.

---

## Basic Troubleshooting

Suppose a computer can communicate with an IP address:

ping 8.8.8.8

but has problems resolving a domain name:

ping example.com

This may indicate a possible DNS-related problem.

Other network problems can also cause similar symptoms, so additional testing may be required.

---

## Learning Note

DNS is an important network service used by computers to resolve domain names into IP addresses.
