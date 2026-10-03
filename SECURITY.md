# Security Policy & Repository Protection

## 1. Public Availability & Integrity Guarantee

This repository is publicly available under the **MIT License**. Anyone is free to:
- Browse, download, and clone the skill.
- Import [`SKILL.md`](SKILL.md) and reference files into their own Claude.ai Projects, Claude Code CLI, Claude Desktop, or AI agents.
- Fork the repository for private adaptations.

### Protection of the Live Upstream Repository
To ensure that **no unauthorized party can modify or replace the live public skill**:
1. **Protected Branch (`main`)**: The `main` branch of this official repository (`dm-jakaria/Shopify-App-Store-Listing-Optimization`) is write-protected. Direct pushes to `main` are restricted exclusively to the repository owner ([JAKARIA](https://github.com/dm-jakaria)).
2. **Pull Request Protocol**: Any community suggestions, improvements, or additions must be submitted via GitHub Pull Requests (PRs). No external contribution can be merged into live code without explicit review and manual approval by the maintainer.
3. **No Embedded Secrets**: This repository contains zero API keys, access tokens, webhook secrets, or private credentials. All guidelines and templates are pure instructional prompts and markdown documentation.

---

## 2. Reporting a Vulnerability or Policy Concern

If you discover a security concern, malicious contribution attempt, or policy violation:
- Please do **not** open a public GitHub issue.
- Instead, contact the maintainer directly at: **[dm.jakaria.247@gmail.com](mailto:dm.jakaria.247@gmail.com)** or via **[dm-jakaria.com/#contact](https://dm-jakaria.com/#contact)**.
- Reports will be acknowledged within 48 hours and resolved promptly.

---

## 3. Safe Usage Guidelines for AI Agents

When executing this skill with Claude or other LLMs:
- Never feed confidential merchant data, unmasked customer PII (Personally Identifiable Information), or production API access tokens into listing copywriting prompts.
- Ensure that generated app listings comply with official [Shopify Partner Program Policies](https://www.shopify.com/legal/partner-terms).
