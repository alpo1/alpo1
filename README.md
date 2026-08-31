# Hi, I'm Aleksandr Polikarpov 👋
### Junior Backend / Full-Stack Developer (Node.js & TypeScript)
📍 **Haifa, Israel** | Israeli citizen & Oleh (2023) — *No sponsorship required*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN-USERNAME)
[![Email](https://img.shields.io/badge/Email-aleksandr.polikarpov%40yahoo.com-D14836?style=for-the-badge&logo=yahoo&logoColor=white)](mailto:aleksandr.polikarpov@yahoo.com)
[![Phone](https://img.shields.io/badge/Phone-+972--54--330--1091-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+972543301091)

---

### 👨‍💻 About Me
Junior Backend / Full-Stack Developer with strong expertise in **Node.js, TypeScript, PostgreSQL, and MongoDB**, combined with a **10+ year background in operations and investment/procurement analysis**. 

- 🛠 Experienced in building layered production-ready architectures (SOLID, separation of concerns).
- 🤖 Leverage **Agentic AI tooling (Claude Code)** in a disciplined *plan-review-approve* workflow, owning and reviewing every change.
- 🌉 Strong background as a technical liaison between business stakeholders and engineering teams.

---

### 🛠 Tech Stack & Skills

- **Languages:** TypeScript, JavaScript (ES6+), SQL, HTML5/CSS3 *(Familiar with: Java)*
- **Back-End:** Node.js, Express, Fastify, REST APIs (13+ endpoints), JWT Auth (cookies/tokens), Zod validation, Streams & Async programming
- **Front-End:** React 18+, Vite, Tailwind CSS, Recharts, Responsive UI
- **Databases & ORM:** PostgreSQL (Neon), MongoDB (Atlas / Mongoose), Prisma, Schema Design, Transactions, Audit Logging
- **Testing & Tools:** Jest, Supertest, Postman, Docker / docker-compose, GitHub Actions (CI/CD), Git & GitHub
- **Deployment & Cloud:** Render, Neon, MongoDB Atlas

---

### 🚀 Featured Projects

#### 📦 [procure-api](https://github.com/alpo1/procure-api) — Procurement Management REST API
> **Layered backend REST API** (routes → controller → service → repository) built with Node.js, TypeScript, and Express.
- **Dual-Database Design:** PostgreSQL (Neon) for ACID transactional core (suppliers, orders, line items) + MongoDB (Atlas) for append-only audit logging.
- **Security & Validation:** Custom RBAC middleware (buyer/admin), JWT with bcrypt, Zod schema validation, and SQL-injection-safe parameterized queries.
- **Key Features:** Streaming CSV import/export (constant $O(1)$ memory usage regardless of file size), integration test suite (Jest, Supertest), Dockerized, and CI/CD via GitHub Actions.
- [💻 View Repository](https://github.com/alpo1/procure-api)

---

#### 🌦 [weather-verify](https://weather-verify-1.onrender.com/) — Forecast-Accuracy Service
> **Full-stack TypeScript monorepo** (`npm workspaces`) deployed live on Render to aggregate and analyze multi-provider forecast accuracy.
- **Architecture:** Fastify + Prisma / PostgreSQL backend paired with a React 18 + Vite + Tailwind + Recharts frontend sharing cross-tier TypeScript types.
- **Pluggable Adapter Registry:** Normalizes multiple external weather sources (Open-Meteo, WeatherAPI, Gismeteo via Cheerio scraping) into a unified format.
- **Automation & Analytics:** Automated data collection via `node-cron` & GitHub Actions cron trigger with isolated per-provider error handling and upstream rate limiting. Calculates MAE (Mean Absolute Error) by provider and lead time.
- [💻 View Repository](https://github.com/alpo1/weather-verify)

---

### 💼 Work & Education Snapshot
- **Technical Support / IT Assistant** — *Alef Farbstein Enterprise & Investment* (Haifa, 2025–2026)
- **Investment & Procurement Management** — *Moscow Metro / FSUE RADON* (2014–2022)
- **Full-Stack Developer Professional Certificate** — *Tel-Ran Educational Center* (2024–2025)
- **Master's in Management** — *State University of Management* (2008–2013)
