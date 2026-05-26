# mythic3011

Full-stack engineer and Information Security student in Hong Kong.  
I build things that work in production, not just in demos.

---

## Projects

### Security & Cryptography
- **[Secure-Instant-Messenger](https://github.com/mythic3011/Secure-Instant-Messenger)** — E2E encrypted messaging app. X25519/AES-256-GCM, Ed25519 identity keys, Argon2id + TOTP 2FA, replay protection, Textual TUI client. Security tests cover replay attacks and ciphertext tampering.

### Full-Stack & Backend
- **[job-Boards](https://github.com/mythic3011/job-Boards)** — Laravel job board with a production security stack: CrowdSec IDS, Prometheus, Grafana, Loki, HMAC auth service, Docker split-plane deployment. Live at [jb.mythic3011.com](https://jb.mythic3011.com).

### Data & Automation
- **[trustpilot-scraper](https://github.com/mythic3011/trustpilot-scraper)** — Modular TypeScript + Playwright extraction pipeline. 12 single-responsibility modules, property-based tests with fast-check.

### Infrastructure & Open Source
- **[rules](https://github.com/mythic3011/rules)** — Maintained fork of Custom_OpenClash_Rules, optimised for Hong Kong: AI service routing, DNS leak prevention, IPv6 support, shell/Python build scripts.

---

## Homelab

```
MacBook ──── OpenWrt router ──── VPS
                │                 │
           DNS enforcement    Portainer
           DoH upstream       CrowdSec
           OpenClash proxy    Prometheus
           Firewall rules     Grafana
                              Nginx reverse proxy
```

Everything containerised. Everything monitored.

---

## CTF

| Year | Event | Result |
|------|-------|--------|
| 2025 | PolyU × NuttyShell Cybersecurity CTF | 🥇 1st place |
| 2024 | PolyU × NuttyShell Cybersecurity CTF | 🥉 2nd runner-up |
| 2023–24 | HKCERT Cyber Security New Generation CTF | Participant |

> There's a flag hidden somewhere in my repos.  
> `ZmxhZ3tub3RfdGhpc19vbmV9` is not it.

---

## Defaults

```
deterministic > magic
fail loudly, never silently
container-first, always
read before edit
authority before patch
no vendor lock-in
PDPO/GDPR by default
```

---

## Currently

- Breaking: homelab Tailscale routing after OpenWrt update
- Building: AI agent workflow runtime for multi-repo development
- Reading: whatever the next CTF challenge requires

---

## Stack

```
Languages   TypeScript · Python · PHP · Bash/Zsh · SQL
Backend     Laravel · FastAPI · Node.js · React
Data        Playwright · Selenium · spaCy · NER
Infra       Docker · Nginx · OpenWrt · Tailscale · Cloudflare
Monitoring  Prometheus · Grafana · Loki · CrowdSec
Crypto      X25519 · AES-GCM · Ed25519 · Argon2id · TOTP
```

---

## Background

- 🏆 **CTF Champion** — PolyU × NuttyShell Cybersecurity CTF 2025
- 🎓 Information Security degree, Hong Kong (in progress)
- 💼 Previously: OSINT pipeline and NER engineering, mapping industry

---

*Also: VRChat, avatar design, homelab tinkerer.*

> Contact via LinkedIn or commit history.
