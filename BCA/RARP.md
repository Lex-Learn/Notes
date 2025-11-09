Uplink: [000_MOC_BCS-041](000_MOC_BCS-041.md)

---
- This protocol is used by ***diskless computer or computer booting for the first time*** to determine it's IP when it knows its MAC address.

## How RARP works:

1. Client boots up and only knows its own MAC address.
2. It sends a RARP request(broadcast) on the LAN.
3. An RARP server on the same network receives the request.
4. The server looks into its mapping table (MAC-TO-IP mapping).
5. The sever sends back an RARP reply with the correct IP address.
6. the client receives its IP and proceeds with the boot operations.


![](../Pictures/rarp-working.webp)