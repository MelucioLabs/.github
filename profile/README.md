# MelucioLabs

Webentwicklung, E-Commerce & Self-Hosted Infrastructure.

## Kundenprojekte

| Projekt | Beschreibung | Stack |
|---------|-------------|-------|
| **[Alte Brennerei Ribbeck](https://alte-brennerei-ribbeck.de)** | Onlineshop mit Bestellsystem, Rechnungsgenerierung, Events & Standorte | React, Node.js, PostgreSQL |
| **Mückenfett** | Künstler-Website für Liedermacher aus dem Havelland (offline) | HTML/CSS, Node.js |

## Interne Tools

| App | Beschreibung | Stack |
|-----|-------------|-------|
| **Kundenportal** | Multi-Tenant-Portal mit Buchhaltung, Ticketsystem, Newsletter, Social Media | React, Node.js, SQLite |
| **Admin Panel** | Zentrales Dashboard für Billing, Kundenverwaltung, Kalender | Node.js, SQLite |
| **KHAI** | KI-Rezeptgenerator mit Diabetiker-Fokus | React, FastAPI, Google Gemini |
| **Auth Service** | Zentrales SSO für alle Apps (JWT, Cookie-basiert) | Node.js, Express |

## Infrastruktur

Alle Apps laufen als Docker-Container auf einem **Hetzner-Cloud-Server** (Produktivsystem), ergänzt um einen **Raspberry Pi 5** als Hot-Standby und Entwicklungsumgebung. Erreichbar über **Cloudflare Tunnel** auf `*.meluciolabs.de`. CI/CD über **GitHub Actions** mit automatischem Deploy per SSH.

## Tech Stack

`React` `Node.js` `Express` `FastAPI` `SQLite` `PostgreSQL` `Docker` `Cloudflare Tunnel` `Tailscale` `GitHub Actions` `Nginx`

---

🌐 [meluciolabs.de](https://meluciolabs.de) · ✉️ kontakt@meluciolabs.de
