# NetBerg Host

Kostenloses Discord-Bot-Hosting mit Panel-Dashboard und Pterodactyl-Anbindung (Vercel).

## Setup

1. Deploy auf Vercel (dieses Repo)
2. Environment Variables:
   - `PTERODACTYL_URL`
   - `PTERODACTYL_API_KEY` (Application API `ptla_…`)
   - `JWT_SECRET`
   - `OWNER_EMAIL=justin@netberg-host.de`
3. Redeploy nach dem Setzen der Vars

## Login

Inhaber: `justin@netberg-host.de`

## Struktur

- `index.html` – Landing
- `login.html` / `dashboard.html` – Panel
- `api/` – Vercel Serverless (Login, Servers, Status)
- `css/` / `js/` – Styles & Logic
