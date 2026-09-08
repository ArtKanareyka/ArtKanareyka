# Hi, I'm Artem 👋

**Senior Frontend Engineer · Angular, TypeScript, RxJS, Nx · 5+ years · building full-stack products on the side**

📍 Remote · UTC+3 (overlaps EU and US East) · English B2

[![Telegram](https://img.shields.io/badge/Telegram-@ArtKanareyka-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/ArtKanareyka)
[![Email](https://img.shields.io/badge/Email-2pizzakanareyka@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:2pizzakanareyka@gmail.com)

---

## About Me

Senior frontend engineer, in Angular since 2021. I design and ship product modules in large **Nx monorepos** — TypeScript, Signals, RxJS, NgRx, internal UI kits, i18n. On my previous product I was the **#1 contributor** with 2,735 commits — 38.1% of the whole repository. Currently in the logistics division at **Wildberries**, the largest e-commerce marketplace in Eastern Europe (100M+ users).

On the side I build and run full-stack products with real users and payments (Angular + NestJS + PostgreSQL), including computer-vision, image-generation and LLM-powered features. I use AI tooling daily: my own **Claude Code sub-agent pipeline** for planning, implementation and review, **OpenClaw** agents, and **local LLMs**.

---

## 🛠 Skills

| Area | Technologies |
|------|--------------|
| **Frontend** | Angular 14–22, TypeScript, Signals, RxJS, NgRx (Store/Effects/Entity/Component Store), Angular Material, Taiga UI, PrimeNG, Tailwind, Bootstrap, SCSS, Chart.js, Storybook, PWA, Capacitor |
| **Architecture** | Nx monorepos, standalone / zoneless, OnPush, design tokens, i18n (Transloco, custom runtime i18n), ESLint module boundaries, OpenAPI-first |
| **Backend** | NestJS, Node.js, Prisma, PostgreSQL, MySQL, PHP 8, REST, WebSocket, JWT/OAuth, YooKassa, Telegram Bot API (grammY) |
| **Tooling / DevOps** | Nx, pnpm, Vite, Webpack, Jest, Docker, GitLab CI/CD, GitHub Actions, Sentry, Prometheus |
| **AI** | Claude Code (custom sub-agents & pipelines), OpenClaw agents, local LLMs (Ollama, Qwen), ComfyUI / FLUX, whisper, vision-LLM via OpenRouter, MediaPipe |

---

## 💼 Experience

### Wildberries — Senior Frontend Engineer (Angular)
**06/2026 – present · Logistics division · Remote**

Angular 21 / Nx monorepo: 9 deployable apps for 5+ countries on 4 groups of shared libraries. 132 commits and 29 closed tickets in the first 3 months.

- Built the **vehicle repair-requests module** from scratch: registry with de-duplication, multi-step form (tractor + trailer), file attachments, draft autosave, step-by-step request card.
- External logistics: trailer tracking and driver split on task cards, elapsed-time tracking in the task registry, route time-control timer.
- Migrated the "Overruns" and "Speeding violations" reports from legacy tables to the internal UI kit and **Angular Signals**.
- Sign-in / sign-up for the public portal cabinet localized into **6 locales** (Transloco, ICU MessageFormat).
- Role-based access to medical data; frontend ↔ backend contract alignment via Swagger codegen.

**Stack:** Angular 21, Signals, NgRx, RxJS, Nx 22, Taiga UI + internal UI kit, Transloco, MapLibre / OpenLayers, Centrifuge, GitLab MRs.

---

### Inschooltech — Frontend Engineer (Angular)
**07/2024 – 04/2026 · 1 yr 10 mo**

B2B SaaS for private schools and kindergartens. **#1 contributor** for the period: 2,735 commits, 38.1% of all repository commits (next contributor: 21.4%).

- Designed and shipped end-to-end **dashboards for three user roles** (parent, student, staff), including a mobile staff workspace.
- Grading journal, schedule module, CRUD planning modules with file uploads, analytics dashboards (Chart.js with custom stacked-bar and doughnut components).
- Migration of the UI layer from **PrimeNG to an internal component library** (6,500+ changes in the shared layer).
- Led the codebase through major Angular upgrades **17 → 18 → 20 → 21**; migrated the repo from npm to **pnpm** with vulnerability remediation.
- Established **OnPush** as the team standard; 115 refactoring commits; code review and mentoring of 2 junior engineers.

**Stack:** Angular 17–21, TypeScript, RxJS, Signals, NgRx, SCSS, Chart.js, pnpm, GitLab CI/CD.

---

### Bazovye Tekhnologii — Frontend Engineer (Angular)
**05/2021 – 07/2024 · 3 yr 3 mo**

E-commerce and corporate web for a construction company: reusable component library, materials cost calculator, NgRx, CRM integration.

**Stack:** Angular 14–20, TypeScript, RxJS, NgRx, SCSS, Bootstrap, Angular Material, Webpack, Vite.

---

## 🚀 Production Side Projects

### 🪞 Forma — men's grooming PWA with AI analysis
**2026 – present · [rost.muzhskoy-rezhim.ru](https://rost.muzhskoy-rezhim.ru)**

AI analysis of face, hairstyle and outfit from a photo, daily checklist, progress tracking, leaderboard, PRO subscription. **13,800+ sign-ups, 221 active paid subscriptions** (YooKassa); paid conversion **1.30% → 2.02%** after a monetization change.

- Migrated the live site from vanilla JS to **Angular 22** (standalone, zoneless, Signals; 142 components) while keeping the running PHP backend (27 REST endpoints) untouched.
- **On-device face detection** in the browser with MediaPipe Tasks Vision.
- **Benchmarked 15 vision LLMs** for quality, variance, latency and cost; moved analysis to gemini-2.5-flash (~$0.0035 per analysis).
- Rebuilt the scoring algorithm and live weekly leaderboard recount; custom runtime i18n with lazy-loaded locales.
- Product decisions driven by metrics read straight from the production DB (paid conversion, retention, repeat payments).

**Stack:** Angular 22, Signals, MediaPipe, Chart.js, Capacitor, PHP 8, MySQL, YooKassa, OpenRouter (Gemini).

---

### 🏗 Foundry — Nx monorepo for four products
**2026 – present · NestJS + Angular**

Nx + pnpm monorepo: **9 apps, 23 shared libraries** (payments, auth, push, mailer, observability, Telegram, LLM/STT), 115 spec files, product isolation enforced with ESLint module boundaries. 1,000 commits.

- **🏋 Kachalka** — fitness bot + Mini App / PWA with Capacitor builds for iOS and Android · peak **5,000+ users** · YooKassa · Jest (unit + E2E).
- **🔒 Kachalka VPN** — VPN service on 3X-UI/Xray · ~100 MAU · Sentry + Prometheus · rate limiting · health checks.
- **🧾 White-label CRM for repair shops** — OpenAPI-first, intake → repair → handout, FIFO inventory, payroll, AI copilot and natural-language reports; Angular SSR marketing site.
- Shared **YooKassa subscription engine**: idempotent confirm-in-transaction, grace periods, refunds, reconciliation.
- AI stack for Kachalka: an **OpenClaw** agent gateway for the Telegram bots, exercise illustration generation (**ComfyUI / FLUX**), voice transcription (whisper).
- Development runs through my own **Claude Code sub-agent pipeline**: planner, implementers, launch checks, reviewer, UX and visual QA; **local LLMs** (Ollama, Qwen) for work that must stay off the cloud.

**Stack:** NestJS 11, Prisma 6, PostgreSQL, grammY, Angular 22 (zoneless, SSR), Jest 30, Nx 23, Docker, GitHub Actions, Sentry, Prometheus, OpenClaw, ComfyUI / FLUX, Ollama.

---

*Always building something in production.*
