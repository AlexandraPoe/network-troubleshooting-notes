# network-troubleshooting-notes

# Network Troubleshooting Notes

## Scenario 1: Cannot access a website

### Step-by-step investigation:
1. Check connectivity (ping)
2. Check route (traceroute)
3. Verify DNS resolution
4. Check service availability (HTTP response)

### Possible causes:
- DNS misconfiguration
- Routing issue
- Server downtime
- Firewall blocking traffic

### Conclusion:
Using a structured troubleshooting approach helps isolate the issue efficiently.

---

## Scenario 2: High latency

### Steps:
1. Measure latency using ping
2. Identify network hops using traceroute
3. Check packet loss
4. Analyze network load

### Possible causes:
- Network congestion
- Routing inefficiencies
- Packet loss

---

## Scenario 3: Calls disconnect at 30 seconds (VoIP-style)

### Steps:
1. Check SIP signaling
2. Verify session timers
3. Inspect firewall/NAT behavior
4. Analyze logs for timeout events

### Possible causes:
- SIP session timeout misconfiguration
- NAT/firewall dropping session
- Incorrect signaling between operators

---

## My Approach

When investigating issues:
1. Understand the symptoms
2. Isolate the layer (network / system / application)
3. Validate assumptions using tools (ping, traceroute, logs)
4. Identify root cause
5. Document findings and resolution
