<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-header-light.svg">
  <img src="assets/profile-header-light.svg" alt="Juan Cardesa — backend engineering with a security mindset" width="100%">
</picture>

# Hi, I'm Juan 👋

**Backend engineering with a security mindset—and a healthy curiosity for how things break.**

I've been curious about computers since I built my first PC at 13. These days, that curiosity goes into backends, APIs, automation, and defensive tools—the kind that catch problems early and explain what happened.

I'm finishing my Software Engineering degree in Seville, Spain, and working towards a junior backend role where I can keep building useful things and asking good questions.

📍 **Seville, Spain** · 🎓 **Finishing Software Engineering** · 🛠️ **Currently building defensive tools**

[Portfolio](https://juancardesa.dev) · [LinkedIn](https://www.linkedin.com/in/juan-cardesa-sosa-a39623258/) · [My flagship project](https://github.com/JuanCardesa/secret-scanner-cli)

## A little more about me

Give me an API, an edge case, or a suspicious assumption and I'll probably want to poke at it. I like projects that are useful, explain themselves, and are honest about what they cannot do yet.

## Things I've been building

### 🔐 The one that looks for secrets

#### [Secret Scanner CLI](https://github.com/JuanCardesa/secret-scanner-cli) · my flagship project

<p align="center">
  <a href="https://github.com/JuanCardesa/secret-scanner-cli">
    <img src="assets/secret-scanner-demo.gif" alt="Terminal demo of Secret Scanner CLI detecting and redacting synthetic secrets" width="820">
  </a>
</p>

A secret removed from the latest file can still be sitting in Git history. I built this defensive Python CLI to scan GitHub repositories and organizations through the API—without cloning them—plus local code and recent commits.

It combines patterns with entropy analysis, redacts matches before reporting, and produces terminal, JSON, HTML, or SARIF output. You can run it as a CI gate or pre-commit hook; it also ships as a [PyPI package](https://pypi.org/project/cardesa-secret-scanner/) and reusable GitHub Action.

`Python` `GitHub API` `SARIF` `pytest` `GitHub Actions`

### 🔎 The one that explains suspicious pages

#### [PhishLens](https://github.com/JuanCardesa/PhishLens)

<p align="center">
  <a href="https://juancardesa.github.io/PhishLens/">
    <img src="assets/phishlens-risk-analysis.png" alt="Controlled PhishLens demo explaining the risk signals on a simulated phishing page" width="820">
  </a>
</p>

I wanted a phishing assistant that did more than flash a red warning. PhishLens explains *why* a page looks risky using URL and privacy-preserving DOM signals, with optional threat intelligence, TLS, domain-age, and ML enrichment.

It pairs a React/TypeScript Manifest V3 extension with a FastAPI backend, without sending full HTML, passwords, form values, or typed emails. The screenshot is a controlled local demo—not a live phishing site.

[Try the project site](https://juancardesa.github.io/PhishLens/) · `TypeScript` `React` `FastAPI` `Manifest V3` `Docker`

### 🧪 The one still growing in the lab

#### [Threat Intel Honeypot](https://github.com/JuanCardesa/Threat-Intel-Honeypot) · work in progress

<p align="center">
  <a href="https://github.com/JuanCardesa/Threat-Intel-Honeypot">
    <img src="assets/honeypot-lab.svg" alt="Threat Intel Honeypot local lab flow from Cowrie events to an anonymized dashboard" width="820">
  </a>
</p>

This is the project where being careful is part of the engineering. I'm building a local Cowrie lab and Python pipeline that parses, anonymizes, enriches, stores, and maps events to possible MITRE ATT&CK techniques.

The pipeline works against synthetic samples and a self-generated local Cowrie capture. It has **not** been exposed to the Internet and doesn't claim any real-world attack data—that step stays behind a deliberate security checklist.

`Python` `Cowrie` `Docker` `SQLite` `MITRE ATT&CK`

## On my workbench right now

- Making the honeypot pipeline deployment-ready without rushing its safety boundaries.
- Going deeper into backend engineering and Application Security.
- Finishing my degree and getting ready for my first junior backend role.

## My usual toolbox

| What for | What I reach for |
| --- | --- |
| **Building backends** | `Python` `FastAPI` `Java` `Spring Boot` `REST APIs` |
| **Thinking defensively** | `Secret detection` `Secure development` `Threat modeling` |
| **Checking my work** | `pytest` `Testing` `GitHub Actions` `Git` |
| **Shipping and storing** | `Docker` `SQL` `MySQL` `SQLite` |
| **Building interfaces when needed** | `TypeScript` `React` |

## Say hello

Interested in backends, defensive security, or a tool that solves an oddly specific problem? I'd be happy to chat.

[LinkedIn](https://www.linkedin.com/in/juan-cardesa-sosa-a39623258/) · [Portfolio](https://juancardesa.dev)
