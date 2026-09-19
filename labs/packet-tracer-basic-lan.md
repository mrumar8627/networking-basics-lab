# Cisco Packet Tracer - Basic LAN Lab

## Objective

To create a simple LAN using two computers and a switch.

---

## Topology

PC1 -------- Switch -------- PC2

---

## Devices

The lab uses:

- 2 PCs
- 1 Switch
- Copper straight-through cables

---

## IP Configuration

Configure PC1:

IP Address: 192.168.1.10
Subnet Mask: 255.255.255.0

Configure PC2:

IP Address: 192.168.1.11
Subnet Mask: 255.255.255.0

A default gateway is not required for communication between these two devices in this simple LAN.

---

## Testing Connectivity

On PC1, open Command Prompt and run:

ping 192.168.1.11

On PC2, run:

ping 192.168.1.10

---

## Expected Result

The two computers should be able to communicate with each other.

A successful test may display:

Reply from 192.168.1.11

---

## Troubleshooting

If the ping fails, check:

1. Are both PCs connected to the switch?
2. Are the cables connected correctly?
3. Are the IP addresses correct?
4. Are both devices using the same subnet?
5. Are the switch ports active?
6. Check the Packet Tracer simulation for errors.

---

## Learning Outcome

This lab demonstrates:

- Basic LAN topology
- Switch connectivity
- IPv4 addressing
- Subnet masks
- Basic network testing
- Basic troubleshooting

---

## Next Step

Future labs can introduce:

- Routers
- Default gateways
- DHCP
- Multiple networks
- Basic routing
