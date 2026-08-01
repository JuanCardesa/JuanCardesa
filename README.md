<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-header-light.svg">
  <img src="assets/profile-header-light.svg" alt="Juan Cardesa — backend engineering with a security mindset" width="100%">
</picture>

# Juan Cardesa

**Backend engineering with a security mindset.**

Software Engineering student in the final stage of my degree, based in Seville, Spain. I build backend systems, developer tools, and defensive security projects with Python/FastAPI and Java/Spring Boot.

[Portfolio](https://juancardesa.dev) · [LinkedIn](https://www.linkedin.com/in/juan-cardesa-sosa-a39623258/) · [Secret Scanner CLI](https://github.com/JuanCardesa/secret-scanner-cli)

I enjoy understanding how systems fail and turning that knowledge into useful software: reliable APIs, practical automation, and security tooling with clear boundaries. That curiosity started early—I built my first computer from scratch when I was 13.

## Selected work

### [Secret Scanner CLI](https://github.com/JuanCardesa/secret-scanner-cli) · flagship project

> A defensive Python CLI for authorized secret scanning across GitHub and local code.

- **Built:** scans repositories and organizations through the GitHub API without cloning, plus local files and recent commit history. Detection combines provider patterns with Shannon entropy and redacts matches before reporting.
- **Solves:** helps find credentials exposed in current code or left behind in Git history.
- **Shows:** async API integration, bounded concurrency, terminal/JSON/HTML/SARIF output, CI gating, a pre-commit hook, a reusable GitHub Action, and a published [PyPI package](https://pypi.org/project/cardesa-secret-scanner/).

`Python` `GitHub API` `SARIF` `pytest` `GitHub Actions`

### [PhishLens](https://github.com/JuanCardesa/PhishLens)

> An explainable phishing-risk assistant built as a Chrome Manifest V3 extension and a FastAPI backend.

- **Built:** a React/TypeScript extension that combines local URL and privacy-preserving DOM signals with optional backend enrichment.
- **Solves:** makes phishing risk easier to inspect by explaining the signals behind a result without sending full HTML, passwords, form values, or typed emails.
- **Shows:** FastAPI endpoints, threat intelligence, TLS and domain-age analysis, optional ML explanations, pytest/Vitest coverage, a real-Chromium smoke test, Docker, and automated CI.

[Live project](https://juancardesa.github.io/PhishLens/) · `React` `TypeScript` `FastAPI` `Manifest V3`

### [Threat Intel Honeypot](https://github.com/JuanCardesa/Threat-Intel-Honeypot) · work in progress

> A safety-first Cowrie lab and Python pipeline for turning honeypot telemetry into structured defensive analysis.

- **Built:** a local Docker Compose baseline and a tested pipeline that parses, anonymizes, enriches, stores, and maps events to possible MITRE ATT&CK techniques.
- **Solves:** creates a repeatable path from semi-structured Cowrie logs to an SQLite dataset and static analysis dashboard.
- **Shows:** threat boundaries, defensive data engineering, unit-tested automation, and honest reporting. It has been validated locally, but **has not been exposed to the Internet and does not claim unsolicited attack data**.

`Python` `Cowrie` `Docker` `SQLite` `MITRE ATT&CK`

## Current focus

- Deepening my backend and Application Security practice.
- Building and validating the Threat Intel Honeypot pipeline before any public deployment.
- Finishing my Software Engineering studies.

## Technical toolkit

| Area | Tools and practices |
| --- | --- |
| **Core** | `Python` `Java` `TypeScript` |
| **Backend** | `FastAPI` `Spring Boot` `REST APIs` |
| **Security** | `Secret detection` `Secure development` `Threat modelling` `MITRE ATT&CK mapping` |
| **Quality & delivery** | `pytest` `Testing` `GitHub Actions` `Git` `Docker` |
| **Data** | `SQL` `MySQL` `SQLite` |

## Let's connect

Interested in backend engineering, defensive security, or building useful developer tools? Let’s connect.

[LinkedIn](https://www.linkedin.com/in/juan-cardesa-sosa-a39623258/) · [Portfolio](https://juancardesa.dev)
