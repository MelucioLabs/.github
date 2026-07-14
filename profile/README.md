# MelucioLabs

Webentwicklung, E-Commerce, KI-Assistenten & Self-Hosted Infrastructure.

## Projekte

| Projekt | Beschreibung | Stack |
|---------|-------------|-------|
| **[M.d.Ä. — Alte Brennerei Ribbeck](https://alte-brennerei-ribbeck.de)** | Buch- und Weltenprojekt „Menelaus der Äonische": Website, Shop mit automatisierter Auslieferung personalisierter E-Books, In-World-Chatbot | Astro, Cloudflare Workers, Stripe, R2, D1 |
| **[KI-Demo](https://meluciolabs.de/ki-demo)** | Persona-Baukasten: KI-Assistent aus Branche, Rolle und Tonfall zusammenstellen und sofort chatten, ohne Anmeldung | Cloudflare Workers AI, RAG |
| **[KHAI](https://kitchenhelper-ai.de)** | KI-Rezeptgenerator mit Diabetiker-Fokus (BE-/KHE-Berechnung) | React, FastAPI, Google Gemini |

## Interne Plattform

| App | Beschreibung | Stack |
|-----|-------------|-------|
| **Kundenportal** | Multi-Tenant-Portal mit Buchhaltung, Ticketsystem, Newsletter, Social Media | React, Node.js, SQLite |
| **Admin Panel** | Zentrales Dashboard für Billing, Kundenverwaltung, Kalender | Node.js, SQLite |
| **Auth Service** | Zentrales SSO für alle Apps (JWT, Cookie-basiert) | Node.js, Express |

## Infrastruktur

Alle Apps laufen als Docker-Container auf einem **Hetzner-Cloud-Server** (Produktivsystem), ergänzt um einen **Raspberry Pi 5** als Hot-Standby und Entwicklungsumgebung. Erreichbar über **Cloudflare Tunnel** auf `*.meluciolabs.de`. CI/CD über **GitHub Actions** mit automatischem Deploy per SSH.

## Tech Stack

`React` `Astro` `Node.js` `Express` `FastAPI` `SQLite` `PostgreSQL` `Docker` `Cloudflare Workers` `Workers AI` `Cloudflare Tunnel` `Tailscale` `GitHub Actions` `Nginx`

---

🌐 [meluciolabs.de](https://meluciolabs.de) · ✉️ kontakt@meluciolabs.de
