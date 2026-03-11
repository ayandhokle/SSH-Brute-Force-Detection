# SSH Brute-Force Detection

## Objective
Simulate and detect an SSH brute-force attack using Splunk in a SOC home lab environment.

## Lab Setup
- Kali Linux (Attacker)
- Ubuntu Server (Target)
- Splunk Enterprise (SIEM)

## Attack Simulation
Hydra was used to generate multiple failed SSH login attempts against an Ubuntu server.

## Detection & Investigation
Splunk was used to analyze Linux authentication logs and identify brute-force activity based on repeated failed login attempts.

## Outcome
The attack was successfully detected through log analysis, demonstrating SOC analyst investigation skills.

## Screenshots
Splunk Searched Queries:-
1. Failed Attempts events:
![Raw Falied Events](Screenshots/01_raw_failed_password.png)<br><br>
2.Brute-force_stats_by_IP:
![Brute-Force-stat](Screenshots/02_brute-force_stat_by_IP.png)<br><br>
3.Targeted User Analysis
![User Analysis](Screenshots/03_targeted_user_analysis.png)
