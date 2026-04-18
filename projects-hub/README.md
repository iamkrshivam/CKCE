# Projects Hub – Framework

This directory defines the rules for submitting **project skeletons** – high‑level descriptions of cybersecurity projects that contributors can later implement. No actual code or full implementations are stored here.

## What qualifies as a cybersecurity project?
- A clearly defined defensive goal (e.g., “build a log parser”, “design a firewall rule visualiser”).
- Must map to one or more CKCE domains.
- Must have a difficulty level (Beginner, Intermediate, Advanced, Research).

## Allowed categories
- **Beginner** – Scripts that automate simple tasks, basic network monitors.
- **Intermediate** – Small tools like a port scanner (educational), log analyser.
- **Advanced** – IDS rule generator, cloud misconfiguration detector.
- **Research** – Novel defence prototypes, machine learning for intrusion detection.

## Connections to domains & careers
Each project must declare:
- `Domains:` (e.g., Network Security, SOC)
- `Careers:` (e.g., SOC Analyst, Security Engineer)
- `Prerequisites:` (skills from the skill graph)

## Submission rules
1. Use the `/templates/PROJECT_TEMPLATE.md`.
2. Place the file in the appropriate domain and difficulty folder (e.g., `/domains/Network-Security/beginner/projects/`).
3. No code, no binaries – only a description, architecture outline, and expected outcomes.
4. All projects must be defensive – no offensive tool skeletons.
