
# SIEM Exclusion Rules — REDACTED

This repository contains **siem** exclusion rules with:
- Author tags normalized to `slenderman39`
- Dates anonymized
- Client-identifying data redacted (IPs, emails, hostnames, GUIDs, SIDs, hashes, usernames in paths, etc.)
- Brand references anonymized (replaced `wazuh` with `siem`)

## Install
Use the appropriate import location for your SIEM platform. For example:
```
/path/to/siem/rules/local.d/local_exclusions.xml
```
Validate with your platform's rule tester, then reload the service.

## Redaction policy
See `SECURITY.md` for high-level policy.
