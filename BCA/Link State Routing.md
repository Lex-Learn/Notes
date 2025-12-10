Uplink: [000_MOC_BCS-041](000_MOC_BCS-041.md)

---
- Link state routing is an algorithm to find the shortest path to a router.
- ## Working
	- Router send "Hello" packet to update their link state about the neighbouring router and the cost.
	- Each router floods the link state on the network.
	- After the router received link state from the other routers they run the Dijkstra's algorithm to find the shortest path to the destination.
- 