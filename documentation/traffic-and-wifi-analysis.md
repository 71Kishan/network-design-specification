# Traffic and Wi-Fi Analysis

## Traffic Capture Method

The project used a SPAN port connected to a laptop for packet capture and analysis with Wireshark. Scheduled capture intervals were used to collect representative traffic during the analysis period.

The documented capture contained approximately **900 MB** of traffic and **6,436,267 packets**.

## Application Traffic Estimates

The analysis documented the following estimated traffic requirements for selected applications:

| Application | Estimated bandwidth |
|---|---:|
| Email | 0.144 Mbps |
| FTP server | 12 Mbps |
| Security cameras | 4.8 Mbps |
| **Combined** | **16.944 Mbps** |

These figures were used as part of the project's bandwidth/capacity assessment.

## Packet Observations

The project documentation noted that the captured traffic was primarily multicast rather than broadcast traffic. The documented frame-size distribution also showed a significant concentration of frames in the 1280–2559 byte range, representing approximately 45% of the captured frames.

## Wi-Fi Mapping

Wi-Fi mapping was performed to assess wireless signal strength, connectivity, speed, and user-facing observations across the environment.

The wireless analysis supported the broader finding that network performance and wireless capacity were areas where improvement could provide operational benefits.

## Interpretation

The traffic analysis was not used as a claim that every observed packet represented user application demand. Instead, it provided measured evidence that was combined with the walkthrough, user survey, and bandwidth estimates when developing the proposed design.

## Portfolio Takeaway

This part of the project demonstrates a practical workflow for infrastructure analysis:

**Capture → Measure → Interpret → Translate findings into capacity/design requirements**
