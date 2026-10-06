# Nathan Le Bourdiec

**Network and security engineering student who deploys AI in production, with guardrails.**
Final-year engineering student at EIGSI La Rochelle, specializing in Network and Information Systems Architecture (graduating 2027).

### Currently building: [palimp](https://github.com/n-le-bourdiec/palimp)

An offline CLI that reconstructs *why* inherited firewall rules exist (Juniper SRX), from configs, commit history, logs and tickets. Each rule gets ranked evidence, a confidence level, a verdict and the question to ask its owner.

- **Safety first:** on 50 held-out synthetic scenarios (7,748 rules), palimp flagged zero live rules for removal, versus 109 for a naive "zero hits means delete" approach, at 91.5% verdict accuracy.
- **Honest evaluation:** seeded simulator with hidden ground truth, held-out runs only in GitHub Actions from a secret the coding agent never sees.
- **AI where it earns its place:** a local LLM writer was measured against deterministic text, did not beat it, and ships off by default. Prompt injection from config text was tested: no injected claim got through.
- **Built with an AI coding agent:** I directed and challenged Claude Code across 20+ sessions. Every decision is recorded in `docs/decisions/`, every session's tokens and cost in `metrics/sessions.csv`.

### What I work with

Juniper and Palo Alto firewalls, network architecture, Python, CI/CD with GitHub Actions, local LLMs (Ollama), evaluation design for AI systems.

### Looking for

A 6-month end-of-studies internship starting between January and March 2027, in **network security** or **AI / MLOps for infrastructure**. Open to relocation, Switzerland preferred.

📫 [LinkedIn](https://www.linkedin.com/in/nathan-le-bourdiec) · n.le-bourdiec.27@edu.eigsi.org
