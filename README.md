# PS229 Cyber Assistant

> An AI-powered cybersecurity assistant that answers security questions, explains vulnerabilities, and guides secure configuration — built for the PS229 practical.

[![Python](https://img.shields.io/badge/Python-3.11+-blue)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-in%20development-yellow)]()

## What it does

PS229 Cyber Assistant is a conversational security tool designed to:

- **Answer security questions** — vulnerabilities, attack vectors, best practices
- **Explain CVEs** — plain-language breakdowns of common vulnerabilities and exposures
- **Guide hardening** — step-by-step secure configuration for Windows and Linux
- **Check configurations** — flag weak settings (passwords, firewalls, updates)

## Status

> ⚠️ **In development** — this repository currently holds the project scaffold.
> The assistant core (LLM integration, security knowledge base, configuration
> checker) is being built. Check back soon.

## Planned architecture

```
┌─────────────┐   ┌──────────────────┐   ┌─────────────────┐
│  CLI / GUI  │──▶│  Assistant core  │──▶│  Security KB    │
│  (chat)     │   │  (LLM + rules)   │   │  (CVE, configs) │
└─────────────┘   └──────────────────┘   └─────────────────┘
                        │
                        ▼
                 ┌─────────────┐
                 │  Hardening  │  (Windows / Linux checks)
                 └─────────────┘
```

## Related

- [PS232 Security Hardening Tool](https://github.com/scar8969/PS232_secutity-hard) — the companion hardening engine this assistant talks to

## License

MIT
