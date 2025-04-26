
# Custom Incident Response Playbook (CICIDS2017+IRC)

## Preparation
- IDS/SIEM tuned with rules for Brute Force, DDoS, Web Attacks, Infiltration.
- Load CICIDS2017 IOCs into detection engines.
- Define severity classification (Low, Medium, High, Critical).
- Assign IR team roles (Detection, Containment, Eradication, Comms).
- Prepare standard communication templates.

## Detection & Initial Triage
- Identify alert from SIEM (Splunk, etc.)
- Correlate multiple alerts
- Classify incident type: Brute Force, DDoS, Web Attack, Botnet
- Assign severity

## Containment Checklist
- Block attacker IPs
- Isolate compromised hosts
- Disable compromised accounts
- Stop malicious processes
- Preserve forensic evidence

## Eradication
- Remove malware
- Patch vulnerabilities
- Validate environment

## Recovery
- Restore systems
- Rotate credentials
- Increase monitoring

## Post-Incident Review
- Root Cause Analysis
- Update detection rules
- Lessons Learned
