# Assignment 1 – Basic Network Topologies Using Switches and Hubs

## How to Test:

1. Open Cisco Packet Tracer.
2. Open exp1_topologies.pkt.
3. Click on any PC (for example, PC0).
4. Go to Desktop → Command Prompt.
5. Run ping commands:

   ping 192.168.10.2
   ping 192.168.10.3
   ping 192.168.10.4

6. Observe successful replies from all devices.

---

## Simulation Mode Test:

1. Switch to Simulation Mode.
2. Use Add Simple PDU or ping commands.
3. Observe packet flow between devices.

---

## Topologies Included:

- Star Topology (Switch-based)
- Hub-based Topology
- Ring-like Topology

---

## Expected Output:

- All PCs should communicate successfully.
- Star topology provides efficient communication.
- Hub topology shows broadcast behavior and collisions.
- Ring topology uses Spanning Tree Protocol (STP) to prevent loops.
- Network continues working even after link failure in ring topology.

---

## Files Included:

- exp1_topologies.pkt
- report_exp1.pdf
- output_exp1.txt