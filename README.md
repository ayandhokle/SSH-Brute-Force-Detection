# Project 2: SSH Brute-Force Detection

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
Splunk Events:-
![Raw Falied Events](Screenshots/01_raw _failed_password.png)
Log Inputs:-
![Log Inputs](Screenshots/02_log_inputs.png)
Failed Login Events:-
![Failed Login Events](Screenshots/03_failed_login_events.png)
Aggregated Failed Login:-
![Aggregated Failed Logins](Screenshots/04_failed_login_stats.png)
