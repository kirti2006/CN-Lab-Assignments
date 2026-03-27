# Assignment 2 – Packet Flow Visualization Using Simulation Mode

## How to Test:

1. Open Cisco Packet Tracer.
2. Open exp2_packetflow.pkt.
3. Click on PC0.
4. Go to Desktop → Command Prompt.
5. Run the command:

   ping 192.168.20.2

6. Switch to Simulation Mode.
7. Click Auto Capture / Play.
8. Observe:
   - ARP Request and ARP Reply
   - ICMP Echo Request and Reply

---

## Second Test (Important):

1. Run the same command again:

   ping 192.168.20.2

2. Observe:
   - No ARP Request
   - Only ICMP packets
   - Faster communication

---

## Expected Output:

- First ping shows ARP + ICMP packets
- Second ping shows only ICMP packets
- Switch learns MAC addresses of devices
- Packet flow visible in Event List

---

## Files Included:

- exp2_packetflow.pkt
- report_exp2.pdf
- output_exp2.txt