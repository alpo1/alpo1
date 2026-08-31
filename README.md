Aleksandr Polikarpov
Junior Backend / Full-Stack Developer — Node.js & TypeScript
Haifa, Israel | aleksandr.polikarpov@yahoo.com | +972 54-330-1091 | LinkedIn | GitHub
Israeli citizen & new immigrant (Oleh, 2023) — fully eligible to work in Israel, no sponsorship required.
SUMMARY
Junior Backend / Full-Stack Developer focused on Node.js, TypeScript, PostgreSQL and MongoDB, with a 10+ year background
in operations and investment analysis. Designed and shipped two production-style projects end to end — a layered procurement
REST API and a live, deployed multi-provider forecast-accuracy service (see Projects). Builds with agentic AI tooling (Claude
Code) in a plan-review-approve workflow, owning every change. Recent technical/IT experience bridging business stakeholders
and a development team.
TECHNICAL SKILLS
Languages: JavaScript (ES6+), TypeScript, SQL, HTML5/CSS3. Familiar with: Java.
Back-end: Node.js, Express, Fastify, REST APIs, JWT authentication, asynchronous programming & streaming, Prisma. Familiar
with: Java/Spring Boot.
Front-end: React, Vite, Tailwind CSS, Recharts, responsive interfaces.
Databases: PostgreSQL, MongoDB (Mongoose), Prisma, schema design, transactions, parameterized queries.
Cloud & Tooling: Neon & MongoDB Atlas, Render, Docker / docker-compose, GitHub Actions (CI/CD), Jest, Supertest, Postman,
Git & GitHub.
AI-assisted development: Claude Code (agentic AI coding) as a primary development tool — plan-review-approve workflow,
owning and reviewing every change.
PROJECTS
procure-api — Procurement management REST API github.com/alpo1/procure-api
•
Backend REST API (13 endpoints) in Node.js, TypeScript and Express on a layered architecture (routes → controller → service
→ repository), applying SOLID and separation of concerns.
•
JWT authentication with bcrypt hashing and role-based access control (buyer / admin) via custom middleware; request
validation with zod; parameterized queries throughout (SQL-injection safe).
•
Dual-database design: PostgreSQL (Neon) for the transactional core — suppliers, orders and line items with foreign keys,
created in a single all-or-nothing transaction — and MongoDB (Atlas) for an append-only audit log.
•
Streaming CSV import/export that never buffers the file in memory (constant memory regardless of size); integration tests (Jest,
Supertest); Docker / docker-compose; GitHub Actions CI runs build + tests on every push.
weather-verify — Forecast-accuracy service (live, deployed) live demo · github.com/alpo1/weather-verify
•
Full-stack TypeScript monorepo (npm workspaces): a Fastify + Prisma / PostgreSQL API and a React 18 + Vite + Tailwind +
Recharts frontend, sharing types through a common package. Deployed live on Render.
•
Integrates three external weather providers (Open-Meteo, WeatherAPI, Gismeteo) behind a pluggable adapter registry —
normalizing REST responses and HTML scraping (cheerio) into one unified shape, so adding a provider is a single entry.
•
Automated daily collection via node-cron plus a GitHub Actions cron trigger, with resilient per-provider error handling (one
provider failing never breaks the others) and graceful upstream rate-limit handling; JWT auth (httpOnly cookie), zod validation.
•
Computes forecast error (MAE) by provider and by lead time; frontend presents a comparison table and error-by-lead-time
charts.
PROFESSIONAL EXPERIENCE
Technical Support / IT Assistant — Alef Farbstein Enterprise & Investment Mar 2025 – Jul 2026
Haifa, Israel · Part-time
•
Acted as technical liaison between business stakeholders and the development team — gathered, analyzed and translated
requirements and feedback for new website features.
•
Performed QA testing on new features before deployment; reported bugs and verified fixes, working closely with developers
throughout the cycle.
•
Contributed to internal technical side projects alongside first-line IT support, network troubleshooting and user-access
management across the Haifa and Tel Aviv offices.
Earlier Career — Investment & Procurement Management — Moscow Metro · FSUE RADON 2014 – 2022
Moscow, Russia · Full-time
•
Owned procurement, investment planning and financial/economic modeling for large logistics and industrial operations —
managing budgets, KPIs and high-value supplier contracts.
•
Coordinated cross-functional project delivery under strict deadlines; promoted to department head within six months for strong
delivery.
Telecom Systems Administrator — State University of Management 2010 – 2012
Moscow, Russia · Full-time
•
Administered Windows / Windows Server environments, networks and infrastructure; managed user accounts, access
credentials and automated backup/recovery systems.
EDUCATION & TRAINING
Professional Certificate — Full-Stack Developer (Node.js / Java) Tel-Ran Educational Center, Israel
•
Full-time program covering Node.js, Express, SQL, React and TypeScript, plus Java/Spring. Final grades 95 / 90.
Master's Degree in Management — Transport Organization Management State University of Management, Moscow, Russia
Feb 2024 – Jun 2025
2008 – 2013
