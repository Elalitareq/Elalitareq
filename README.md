# Hi, I'm Tareq El-Ali 👋

**Full-stack engineer who ships and operates the products I build.** I design products end to end — data model, API, offline-first UI, and the pipeline that puts it in production on Cloudflare or a Linux box I operate myself.

Building for clinics, shops, salons, ISPs and utilities.

---

## What I build

| Area | Things I've shipped |
|---|---|
| **Business software** | Dental clinic management (offline-first PWA + Electron desktop, en/fr/ar with RTL), supermarket stock & POS, salon booking, medical-sales ERP, retail ERP platform with tax and invoicing |
| **Billing & operations** | Electric-generator subscription billing with invoicing, printing and PWA install; ISP/customer management with headless-browser balance scraping |
| **E-commerce** | Multi-tenant storefront + admin on Cloudflare, SEO-driven Lebanese storefront, coffee-shop ordering app |
| **Systems & tooling** | Rust browser-engine experiments, a Go TLS-fingerprint fetcher packaged for npm, crypto backtesting and strategy research in Python |

## DevOps & delivery

I treat deployment as part of the product, not an afterthought.

- **Edge / serverless:** Cloudflare Workers, Pages, D1, R2, Durable Objects (SQLite), Wrangler, custom domains and DNS
- **Self-hosted:** Linux VPS behind Cloudflare — nginx reverse proxy, systemd services, scripted deploy and rollback, health checks
- **CI/CD:** GitHub Actions for test → build → deploy (staging and production), Android and Windows release builds, Rust lint/release pipelines
- **Containers:** Docker and docker-compose for local stacks and services
- **Quality gates:** typed APIs, unit + e2e tests (Playwright), accessibility and dark-mode contrast guards, security review before merge
- **Practices:** trunk-based flow with short-lived feature branches and worktrees, atomic commits, backups and restore drills for SQLite/Postgres data

## Tech I work with

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/-Next.js-000?logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white)
![Hono](https://img.shields.io/badge/-Hono-E36002?logo=hono&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![Electron](https://img.shields.io/badge/-Electron-47848F?logo=electron&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?logo=flutter&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000?logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?logo=playwright&logoColor=white)

## Live work

- 🦷 [dental.elalitareq.com](https://dental.elalitareq.com) — clinic management demo (offline-first, multilingual)
- 💈 [salon.elalitareq.com](https://salon.elalitareq.com) — salon booking and management demo, six switchable designs

## How I work

- Offline-first and multilingual (English / French / Arabic, RTL) by default
- Small, verifiable changes: tests and e2e before merge, deploy scripts that can roll back
- Documentation written for the next person (handover docs, setup guides, architecture notes)
- Heavy use of AI-assisted workflows (Claude Code) with parallel agents, always behind review and tests

---

Most of my client and product code lives in private repositories; happy to walk through any of it on a call.
