# MelucioLabs

Software Development & Self-Hosted Apps auf einem Raspberry Pi 5 Homelab.

## Apps

| App | Beschreibung | Stack |
|-----|-------------|-------|
| **KHAI** | KI-Rezeptgenerator mit Diabetiker-Fokus | React, FastAPI, OpenAI |
| **Lernkarten** | Spaced Repetition mit Leitner-System | FastAPI, SQLite |
| **Palworld Wiki** | Deutsches Wiki mit Pal-Datenbank | React, Express, SQLite |
| **Pi-Stats** | Echtzeit System-Monitoring Dashboard | FastAPI, psutil |

## Infrastruktur

Alle Apps laufen als Docker-Container auf einem Raspberry Pi 5, erreichbar ueber Cloudflare Tunnel auf `*.meluciolabs.de`. Zentrales SSO ueber einen eigenen Auth-Service mit JWT-Cookies.

## Tech-Stack

`React` `FastAPI` `Express` `SQLite` `Docker` `Cloudflare Tunnel` `Tailscale` `GitHub Actions`
