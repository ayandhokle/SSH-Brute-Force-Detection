## Investigation Summary
Multiple failed SSH login attempts were observed from a single source IP.

## Evidence
- Failed password events in auth.log
- High login failure count from attacker IP

## Conclusion
Activity consistent with SSH brute-force attack. No successful authentication detected.
