
---

## Tools Hub

### `tools-hub/README.md`
```markdown
# Tools Hub – Framework

The Tools Hub holds **descriptions** of defensive cybersecurity tools. No actual tool code, binaries, or installation scripts are allowed. Contributors may explain a tool’s purpose, architecture, and typical usage in a defensive context.

## Defensive‑only policy
- ✅ Allowed: Nmap (for network inventory), Wireshark (traffic analysis), ClamAV (antivirus), OSSEC (HIDS).
- ❌ Forbidden: Exploit frameworks (Metasploit offensive modules), password crackers (Hashcat for attacking), any tool primarily designed for unauthorised access.

## Tool categories
- Network tools (e.g., Zeek, Snort)
- Application security tools (e.g., OWASP ZAP, SAST linters)
- SOC tools (e.g., TheHive, MISP)
- Cloud security tools (e.g., ScoutSuite, Prowler)
- IAM tools (e.g., Keycloak, OpenLDAP)
- Forensics tools (e.g., Autopsy, Volatility)
- Threat intelligence tools (e.g., OpenCTI, YARA)

## Contribution guide
Use `/templates/TOOL_TEMPLATE.md`. Place the file under `/domains/<domain>/tools-used/`. Each tool description must include: name, category, defensive use case, required permissions (e.g., root), and ethical warnings (e.g., “do not run on networks you do not own”).
