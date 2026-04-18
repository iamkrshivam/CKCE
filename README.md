# Cybersecurity Knowledge & Career Ecosystem (CKCE)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Contribution Guidelines](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](./community-system/CONTRIBUTING.md)
[![Defensive Only](https://img.shields.io/badge/defensive%20only-Yes-blue)](./community-system/CODE_OF_CONDUCT.md)

## Project Vision

CKCE is a global, open‑source **framework** for structuring cybersecurity knowledge, learning paths, and career development. It is **not** a collection of exploits or real data; it is a **blueprint** that enables thousands of contributors to collaboratively build a comprehensive, domain‑driven encyclopedia of **defensive cybersecurity**.

The ecosystem serves three primary functions:

- **Structured learning system** – Organised by difficulty and domain, from beginner to research.
- **Career roadmap engine** – Maps domains, skills, and projects to real‑world job roles.
- **Contribution‑based knowledge graph** – A modular, extensible graph of concepts, resources, and case studies.

All content added by contributors must be **defensive only**, education‑focused, and follow the governance rules defined in this repository.

---

## Ecosystem Overview (with links)

| Directory | Purpose | Key files |
|-----------|---------|------------|
| [`/domains`](./domains) | 14 core cybersecurity domains, each with difficulty levels and contribution guidelines. | [`/domains/Network-Security/README.md`](./domains/Network-Security/README.md) (example) |
| [`/career-system`](./career-system) | Career definitions, skill graphs, and domain‑to‑job mappings. | [`CAREER_OVERVIEW.md`](./career-system/CAREER_OVERVIEW.md), [`JOB_MAPPING.md`](./career-system/JOB_MAPPING.md) |
| [`/projects-hub`](./projects-hub) | Rules for submitting project ideas and skeletons (no code). | [`PROJECT_STRUCTURE.md`](./projects-hub/PROJECT_STRUCTURE.md) |
| [`/tools-hub`](./tools-hub) | Defensive tool descriptions, categories, and contribution rules. | [`TOOL_CONTRIBUTION_GUIDE.md`](./tools-hub/TOOL_CONTRIBUTION_GUIDE.md) |
| [`/ctf-hub`](./ctf-hub) | Framework for Capture The Flag write‑ups (defensive, educational). | [`CTF_STRUCTURE.md`](./ctf-hub/CTF_STRUCTURE.md) |
| [`/case-studies`](./case-studies) | Guidelines for real‑world incident analysis (no sensitive data). | [`CASE_STUDY_GUIDE.md`](./case-studies/CASE_STUDY_GUIDE.md) |
| [`/knowledge-base`](./knowledge-base) | High‑level domain scopes and cross‑domain relationships. | [`NETWORK_SECURITY.md`](./knowledge-base/NETWORK_SECURITY.md) |
| [`/learning-paths`](./learning-paths) | Step‑by‑step curricula for specific roles and skill levels. | [`SOC_PATH.md`](./learning-paths/SOC_PATH.md), [`CLOUD_SECURITY_PATH.md`](./learning-paths/CLOUD_SECURITY_PATH.md) |
| [`/resources-system`](./resources-system) | Categorisation of books, websites, platforms, and career resources. | [`BOOKS_GUIDE.md`](./resources-system/BOOKS_GUIDE.md), [`DOMAIN_RESOURCES_GUIDE.md`](./resources-system/DOMAIN_RESOURCES_GUIDE.md) |
| [`/community-system`](./community-system) | Contribution workflow, code of conduct, review process, and governance. | [`CONTRIBUTING.md`](./community-system/CONTRIBUTING.md), [`GOVERNANCE.md`](./community-system/GOVERNANCE.md) |
| [`/templates`](./templates) | Strict formatting templates for all contributions. | [`PROJECT_TEMPLATE.md`](./templates/PROJECT_TEMPLATE.md) |

---

## Contribution Philosophy

CKCE is a **framework only** – no actual projects, tools, or write‑ups are included in this skeleton. Contributors will add content later, following the rules defined in each directory.

- **Defensive first** – No attack implementations, malware, or offensive exploit code.
- **Structured** – Every addition must respect the folder hierarchy and use provided templates.
- **Reviewed** – Pull requests are reviewed by domain maintainers.
- **No duplication** – Content must be original or properly referenced.

To start contributing, please read:
1. [`/community-system/CONTRIBUTING.md`](./community-system/CONTRIBUTING.md)
2. [`/community-system/CODE_OF_CONDUCT.md`](./community-system/CODE_OF_CONDUCT.md)
3. The domain‑specific `CONTRIBUTING.md` inside the domain you wish to help (e.g., [`/domains/Network-Security/CONTRIBUTING.md`](./domains/Network-Security/CONTRIBUTING.md)).

---

## Ethical Cybersecurity Statement

CKCE strictly supports **defensive cybersecurity education**, **blue team practices**, and **ethical research**. Any content that promotes illegal activities, active exploitation, or real‑world harm is forbidden. All case studies must anonymise sensitive data and be used solely for learning.

---

## Navigation Guide – Where to start?

| I want to… | Go here |
|-------------|---------|
| Understand the 14 cybersecurity domains | [`/domains`](./domains) |
| See how domains map to job roles | [`/career-system/JOB_MAPPING.md`](./career-system/JOB_MAPPING.md) |
| Follow a guided curriculum | [`/learning-paths`](./learning-paths) |
| Propose a project skeleton | [`/projects-hub`](./projects-hub) |
| Describe a defensive tool | [`/tools-hub`](./tools-hub) |
| Write a CTF write‑up (educational) | [`/ctf-hub`](./ctf-hub) |
| Analyse a real incident (anonymised) | [`/case-studies`](./case-studies) |
| Understand a domain’s scope | [`/knowledge-base`](./knowledge-base) |
| Find books, courses, or labs | [`/resources-system`](./resources-system) |
| Learn the contribution workflow | [`/community-system/CONTRIBUTING.md`](./community-system/CONTRIBUTING.md) |
| Use a template for a new contribution | [`/templates`](./templates) |

---

## Long‑Term Roadmap

- **Phase 1 (current)** – Framework skeleton, governance, templates. ✅
- **Phase 2** – Community onboarding, initial domain content (theory, definitions).
- **Phase 3** – Resource and book catalogues, career progression examples.
- **Phase 4** – Project and tool skeletons, CTF write‑up collection.
- **Phase 5** – Automated knowledge graph visualisation and skill dependency mapping.

---

## License

This repository – the documentation framework, structure definitions, and governance rules – is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
See the [`LICENSE`](./LICENSE) file for details.

All contributed content (future additions) will be subject to the same license unless explicitly agreed otherwise by the maintainers.

---

*Maintained by the CKCE open‑source community.*  
**Questions?** Open an issue in the [Issues](../../issues) tab (template available in [`/community-system/ISSUE_TEMPLATE.md`](./community-system/ISSUE_TEMPLATE.md)).
