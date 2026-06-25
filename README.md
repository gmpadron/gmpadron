# Gabriel Padron

**Full-Stack Software Engineer & Cloud Architect**

6+ years building and operating production systems across ecommerce, SaaS, and financial
platforms. End-to-end ownership — from system design through Kubernetes deployment and production
monitoring. Previously at Cognizant, currently at PimentaFull.

[![Email](https://img.shields.io/badge/Email-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:gm.padron@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gmpadron/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=About.me&logoColor=white)](https://gmpadron.com/)

> *"Architecture is not about choosing the best technology — it's about choosing the right constraints."*

---

## Technical Competencies

**Languages & Frameworks** — TypeScript · JavaScript · PHP · Rust · React · Next.js · Angular · Astro · Node.js · NestJS · Express · Laravel · Inertia.js · Tailwind · HTML/CSS

**Cloud & Infrastructure** — AWS · Cloudflare · Docker · Kubernetes · Proxmox · Nginx · Linux · Bash · CI/CD (GitHub Actions) · Vite

**Data & APIs** — PostgreSQL · SQLite · REST · GraphQL (Apollo) · CQRS · Prisma · Stripe · Meta Graph API

**AI & Automation** — LLMs · RAG · GPU Inference · n8n · Claude Code · Claude Projects

**E-commerce & Marketing** — VTEX IO · Shopify · Liquid · Google Analytics · Google Tag Manager · Google Ads · Meta Pixel

**Architecture & Practices** — Microservices · System Design · Multi-Tenant SaaS · Financial Systems · Agile / Scrum

---

## Featured Projects

**Self-Hosted Email Server + Custom Webmail**
Multi-domain mail server on Mailcow with a custom webmail built in Astro SSR (IMAP login, TOTP 2FA,
account management via API). Solved residential-IP deliverability (listed on Spamhaus/Barracuda, no
editable PTR) by routing send through an authenticated SMTP relay with aligned SPF/DKIM/DMARC; TLS
issued via DNS-01 to coexist with an existing nginx edge.
`Mailcow` `Astro SSR` `Postfix/Dovecot` `Docker` `TypeScript` `Cloudflare`

**litAz — Multi-Client Commercial Management SaaS Platform**
6-service ecosystem covering the full commercial cycle: catalog, multi-warehouse inventory, CQRS
orders, salesperson mobile app, carriers, and Venezuelan fiscal invoicing (SENIAT). Namespace-per-client
isolation on Kubernetes, distributed JWT auth verified offline (no central validator), and a Rust fiscal
engine with a chained SHA-256 integrity ledger.
`NestJS` `Rust` `Angular` `Kubernetes` `PostgreSQL` `CQRS`

**Meta Ads — BI & Reporting Dashboard**
Internal BI tool: aggregates multiple ad accounts behind a Node/Express proxy, keeps its own historical
SQLite cache (background sync with batching/backoff), and cross-references spend × revenue × product ×
audience — with AI-ready exportable reports.
`Node.js` `Express` `SQLite` `React` `Meta Graph API` `Docker`

**Air-Gapped AI Automation with Local GPU Inference**
Self-hosted AI infrastructure with local GPU inference and a RAG pipeline over proprietary databases —
zero internet dependency, full data sovereignty.
`n8n` `LLMs` `RAG` `Docker` `Linux`

**En Roux — Production Ecommerce Store** ([rouxgarments.us](https://rouxgarments.us))
Laravel + React via Inertia.js (no separate REST API), Stripe checkout with idempotent webhooks, and
per-variant transactional stock. Owned the **front-end, architecture, and DevOps** (paired with a backend
engineer); deployed on a Linux cloud server with nginx routing.
`Laravel` `React` `Inertia.js` `Stripe` `Nginx`

---

## Key Achievements

- **60% page-load reduction** on a production ecommerce storefront via systematic profiling
- **Production storefronts delivered** — Triya & Sidewalk on VTEX IO, plus the PimentaFull institutional site on Next.js / AWS / Cloudflare
- **Zero inventory discrepancies** across distributed warehouses via pessimistic locking
- **Immutable, audit-ready fiscal ledger** (chained SHA-256) with multi-currency support and regulatory exports (PDF/XML/TXT)
- **Self-hosted, multi-domain email server** with INBOX deliverability solved (authenticated relay + aligned SPF/DKIM/DMARC)
- Led a legacy-to-modern data reconciliation restoring inventory integrity across systems, and built a secure Admin Panel for operations teams

---

*Languages: Spanish (Native) · Portuguese (Fluent) · English (Basic)*
