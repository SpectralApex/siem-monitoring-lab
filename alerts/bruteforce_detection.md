# Brute Force Detection Rule

## Detection Logic

Detect multiple failed login attempts from the same IP address within a short period.

## Example Detection Criteria

- 5 failed login attempts
- Within 2 minutes
- Same source IP

## Example Response Actions

- Generate SIEM alert
- Notify SOC analyst
- Trigger incident workflow
- Block suspicious IP

## MITRE ATT&CK Mapping

- Technique: T1110 — Brute Force
