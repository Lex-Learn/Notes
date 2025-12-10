Uplink: [000_MOC_BCS-041](000_MOC_BCS-041.md)

---
- ARP stands for "Address resolution protocol".
- It's used to find the *MAC*  address of a device if only IP is know on LAN.

## Working
- Computer A wants to send data to computer B. It knows B's IP.
- ARP request (broadcast):
	- Computer A sends a broadcast message to all devices on the LAN.
- ARP reply (unicast):
	- The device with the IP (computer B) sends a direct reply to computer A (sending MAC address to computer A).
- MAC address store.
	- Computer A stores this information in its ARP cache for future use.
- Data transmission begins:
	- Now that the computer A knows the MAC address, it sends the data directly to computer B.

## Diagram
![](../Pictures/system_.webp)