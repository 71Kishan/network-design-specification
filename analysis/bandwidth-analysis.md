# Bandwidth Analysis

## Objective

The traffic-analysis phase estimated application bandwidth requirements and compared observed network conditions with expected demand.

## Documented Application Requirements

| Application | Distribution | Simultaneous Sessions | Average Transaction Size | Estimated Capacity |
|---|---:|---:|---:|---:|
| E-Mail | 100% | 0.09 | 200 KB | 0.144 Mbps |
| FTP Server | 100% | 1 | 1500 KB | 12 Mbps |
| Security Cameras | 100% | 0.75 | 800 KB | 4.8 Mbps |
| **Total** | | | | **16.944 Mbps** |

## Email Calculation

The source presentation shows the following calculation:

```text
200 KB × 0.09 sessions/second = 18 KB/s
18 KB/s × 8 = 144 Kb/s
144 Kb/s ÷ 1000 = 0.144 Mbps
```

The three documented application estimates combine to:

```text
0.144 Mbps + 12 Mbps + 4.8 Mbps = 16.944 Mbps
```

## Existing Internet Capacity

The requirements analysis documented a 50 Mbps / 50 Mbps fiber Internet connection. The project identified performance issues during periods of high activity and when employees accessed or transferred large cloud files.

The application estimate of 16.944 Mbps represents only the explicitly modeled email, FTP-server, and security-camera traffic. It should not be interpreted as the complete bandwidth demand of the organization.

## Proposed Capacity Improvement

The logical-design phase evaluated higher-speed business Internet options:

- MNSi for Business — 500/500 Mbps
- Gigabit Business Fibe — 940/940 Mbps

The project selected the MNSi option in its documented physical/cost plan.

## Interpretation

The key engineering conclusion was not simply that the modeled applications exceeded 50 Mbps—they did not. Rather, the project identified insufficient available network performance under real operating conditions, including cloud usage, high employee activity, and wireless constraints. The bandwidth model therefore served as one input into the broader capacity-planning decision.

## Scope Note

All figures in this document are project-era measurements, estimates, or proposed values from the original 2023 project. They are not current measurements of the client's network.
