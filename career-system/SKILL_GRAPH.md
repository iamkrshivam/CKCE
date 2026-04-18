# Skill Graph Framework

The CKCE skill graph is a directed acyclic graph (DAG) of skills grouped by domains. Each skill is a node with:

- **Name** – e.g., “Packet Analysis”
- **Domain** – Network Security
- **Difficulty** – Beginner/Intermediate/Advanced/Research
- **Prerequisites** – Other skill nodes
- **Related careers** – SOC Analyst, Incident Responder

No actual graph data is stored in this skeleton. Instead, contributors will populate skill definitions in Markdown files under each domain’s `/beginner`, `/intermediate`, etc. The graph relationships will be expressed via `Prerequisites:` lines.

Example (future content):
```markdown
# Skill: TCP/IP Basics
Domain: Network Security
Difficulty: Beginner
Prerequisites: None
Careers: SOC Analyst, Network Engineer
