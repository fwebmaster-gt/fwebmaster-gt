<h1 align="center">Freddy Gutierrez</h1>

<p align="center">
  <strong>Full Stack Engineer · SaaS · Offline-first mobile · Fintech</strong><br/>
  7+ years shipping production web and mobile products with TypeScript end to end.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/fwebmaster/"><img src="https://img.shields.io/badge/LinkedIn-fwebmaster-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://play.google.com/store/apps/details?id=com.fwebmaster.fwallet"><img src="https://img.shields.io/badge/Google_Play-fWallet-414141?style=flat-square&logo=googleplay&logoColor=white" alt="fWallet on Google Play"/></a>
  <a href="https://wallet.fwebmaster.com/"><img src="https://img.shields.io/badge/Web_App-wallet.fwebmaster.com-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="fWallet Web App"/></a>
</p>

---

### About

I build **real products that run in production** — mostly SaaS platforms and mobile apps where the
hard parts are data integrity, offline operation and money that has to add up.

- Design APIs and data models that stay correct under concurrency (row locks, idempotent retries, audit trails).
- Build mobile apps that **work fully offline** and reconcile with the server later.
- Own features end to end: schema → API → web → mobile → release.

Most of my work lives in **private, commercial repositories**. This page summarizes what I've built and how;
code review access can be granted on request.

---

### Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,react,nextjs,tailwind,postgres,prisma,sqlite,docker,firebase,git&perline=12" alt="Tech stack"/>
</p>

| Area | Tools |
|---|---|
| **Frontend** | React, Next.js (App Router), TailwindCSS, TypeScript |
| **Mobile** | React Native (Expo), SQLite, offline sync |
| **Backend** | Node.js, NestJS, REST, OpenAPI/Swagger, JWT + refresh tokens, RBAC |
| **Data** | PostgreSQL, Prisma, SQLite, migrations and safe schema evolution |
| **Infra** | Docker, cloud storage, CI |

---

### Featured work

#### fWallet — personal finance platform &nbsp;`Production`

Helps people understand and control their money through analytics, budgets and debt tracking — online or offline.

| | |
|---|---|
| **Platforms** | Android · Web (PWA) |
| **Features** | Accounts, transactions, categories & budgets, cash-flow analytics, debt tracking (owed / lent), offline mode with sync |
| **Architecture** | React Native + Expo with SQLite locally · Next.js web app · NestJS REST API |
| **Links** | [Google Play](https://play.google.com/store/apps/details?id=com.fwebmaster.fwallet) · [Web App](https://wallet.fwebmaster.com/) |

#### SaaS backend foundation &nbsp;`Production · private`

Reusable NestJS + PostgreSQL base used to start new SaaS products without rebuilding the plumbing.

- Authentication with JWT + refresh tokens, role-based access control
- Multi-organization (multi-tenant) architecture
- Consistent pagination, filtering and API conventions

#### Offline-first sync engine &nbsp;`Production · private`

Data layer for apps that must keep working without connectivity and sync later.

- Local-first storage with transaction sync queues
- Conflict handling and idempotent uploads
- Analytics computed on-device

---

### Open source

| Project | Description |
|---|---|
| [firebase-react-tools](https://github.com/fwebmaster-gt/firebase-react-tools) | Firebase helpers for React apps |
| [simple-reactjs-store](https://github.com/fwebmaster-gt/simple-reactjs-store) | Minimal React store built on the Context API |

---

### Currently focused on

SaaS products · financial software · offline-first applications · scalable API architecture

### Let's talk

Open to conversations with teams building serious products. Reach me on
[LinkedIn](https://www.linkedin.com/in/fwebmaster/) — if you'd like to review code from a private project,
ask and I'll grant temporary read access.
