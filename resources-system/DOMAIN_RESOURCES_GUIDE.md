# Domain Resources Guide – Classification Schema

This guide defines how contributors will later add **learning resources** (articles, video tutorials, documentation) to each domain.

## Resource categories
- **Web security resources** – OWASP, secure coding tutorials.
- **Cloud security resources** – Provider‑specific security docs, courses.
- **Networking resources** – Protocol deep dives, firewall design guides.
- **IAM resources** – Identity federation tutorials, LDAP walkthroughs.
- **GRC resources** – Framework PDFs, risk management templates.
- **AI security resources** – Adversarial ML papers, defensive AI guides.

## Metadata required for each resource (placeholder)
```markdown
- Title: [Name]
- Domain: [one of the 14 domains]
- Difficulty: Beginner/Intermediate/Advanced/Research
- Type: Article / Video / Documentation / Interactive lab
- Cost: Free / Freemium / Paid
- Description: (one sentence)
```
Placement
Resources are not stored in /resources-system but referenced in each domain’s README.md under a “Recommended Resources” section (future). This file only defines the schema.

Submission rule
When contributors add a resource reference, they must use the above metadata format and ensure the resource is defensive and not outdated (no deprecated technologies without disclaimer).
