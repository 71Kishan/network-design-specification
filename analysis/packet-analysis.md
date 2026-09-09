# Packet Analysis

## Capture Method

The project used a SPAN port connected to a laptop for packet capture and analysis. Wireshark was used for traffic inspection, with Task Scheduler used to automate recurring capture intervals.

The documented capture process collected approximately **900 MB** of traffic over the analysis period. Captures were scheduled for **7 minutes every half hour**, and the referenced analysis recorded **6,436,267 packets**.

## Key Findings

### Packet-size distribution

The largest documented packet-size distribution was in the **1280–2559 byte** range, representing approximately 45% of the analyzed packet distribution.

### Broadcast and multicast

The project documented:

- 18,361 broadcast packets
- 51,772 multicast packets

The analysis noted that multicast traffic was more prevalent than broadcast traffic in the captured data.

### Highest-traffic host

The analysis identified host **10.150.8.2** as responsible for the highest amount of transmitted/received data in the captured traffic.

Because this is a historical project observation, the host address is presented only as part of the original analysis and should not be interpreted as a current production-network address.

## Engineering Interpretation

The packet capture provided empirical evidence for the broader network assessment. It complemented the user survey, site walkthrough, Wi-Fi mapping, and application-bandwidth estimates rather than serving as the sole basis for the proposed redesign.

## Scope Note

The capture results are from the original 2023 project. No claim is made that these traffic characteristics represent the client's network today.
