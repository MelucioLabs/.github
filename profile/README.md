# MelucioLabs

Software Development & Self-Hosted Apps on a Raspberry Pi 5 Homelab.

## Apps

| App | Description | Stack |
|-----|-------------|-------|
| **KHAI** | AI recipe generator with diabetes-friendly focus | React, FastAPI, OpenAI |
| **Lernkarten** | Spaced repetition with Leitner system | FastAPI, SQLite |
| **Pi-Stats** | Real-time system monitoring dashboard | FastAPI, psutil |

## Infrastructure

All apps run as Docker containers on a Raspberry Pi 5, accessible via Cloudflare Tunnel at `*.meluciolabs.de`. Centralized SSO through a custom auth service with JWT cookies.

## Tech Stack

`React` `FastAPI` `SQLite` `Docker` `Cloudflare Tunnel` `Tailscale` `GitHub Actions`

---

<details>
<summary>🇩🇪 Deutsch</summary>

Software Entwicklung & Self-Hosted Apps auf einem Raspberry Pi 5 Homelab.

### Apps

| App | Beschreibung | Stack |
|-----|-------------|-------|
| **KHAI** | KI-Rezeptgenerator mit Diabetiker-Fokus | React, FastAPI, OpenAI |
| **Lernkarten** | Spaced Repetition mit Leitner-System | FastAPI, SQLite |
| **Pi-Stats** | Echtzeit System-Monitoring Dashboard | FastAPI, psutil |

### Infrastruktur

Alle Apps laufen als Docker-Container auf einem Raspberry Pi 5, erreichbar ueber Cloudflare Tunnel auf `*.meluciolabs.de`. Zentrales SSO ueber einen eigenen Auth-Service mit JWT-Cookies.

</details>
