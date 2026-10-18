# SOC Home Lab

A small, isolated lab for practising detection and investigation.

## Architecture
![Lab diagram](diagrams/lab-diagram.png)

## Components
| Machine | OS | RAM | Role |
|---|---|---|---|
| win-client | Windows 10 | 4 GB | Target, runs Sysmon |
| dc01 | Windows Server Core | 2 GB | Domain controller |
| kali | Kali Linux (headless) | 2 GB | Attack simulation |
| Wazuh server | Ubuntu (cloud free tier) | n/a | SIEM |

## Log flow
Describe how events travel: Sysmon / Windows Event Log -> agent -> SIEM -> dashboard.

## Attacks simulated
| Technique (MITRE ID) | Tool used | Detected? | Notes |
|---|---|---|---|
| T1110 Brute Force | | | |

## What I learned
Short, honest paragraph.

## Limitations
What this lab does not cover.
