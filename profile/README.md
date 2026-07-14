# MelucioLabs

Webentwicklung, E-Commerce & Self-Hosted Infrastructure.

## Apps & Plattform

| App | Beschreibung | Stack |
|-----|-------------|-------|
| **Kundenportal** | Multi-Tenant-Portal mit Buchhaltung, Ticketsystem, Newsletter, Social Media | React, Node.js, SQLite |
| **Admin Panel** | Zentrales Dashboard für Billing, Kundenverwaltung, Kalender | Node.js, SQLite |
| **[KHAI](https://kitchenhelper-ai.de)** | KI-Rezeptgenerator mit Diabetiker-Fokus | React, FastAPI, Google Gemini |
| **Auth Service** | Zentrales SSO für alle Apps (JWT, Cookie-basiert) | Node.js, Express |

## Infrastruktur

Alle Apps laufen als Docker-Container auf einem **Hetzner-Cloud-Server** (Produktivsystem), ergänzt um einen **Raspberry Pi 5** als Hot-Standby und Entwicklungsumgebung. Erreichbar über **Cloudflare Tunnel** auf `*.meluciolabs.de`. CI/CD über **GitHub Actions** mit automatischem Deploy per SSH.

## Tech Stack

`React` `Node.js` `Express` `FastAPI` `SQLite` `PostgreSQL` `Docker` `Cloudflare Tunnel` `Tailscale` `GitHub Actions` `Nginx`

---

🌐 [meluciolabs.de](https://meluciolabs.de) · ✉️ kontakt@meluciolabs.de
