<p align="center">
  <img src="assets/banner-v3.svg" width="100%" alt="William Nayar, backend and distributed systems"/>
</p>

<p align="center">
  <b><a href="https://www.linkedin.com/in/william-nayar/">LinkedIn</a></b>
  &nbsp;·&nbsp;
  <b><a href="mailto:wnayar98@gmail.com">Email</a></b>
</p>

<p align="center">
Final-year CS at NUS specialising in Software Engineering. I build backend systems and care about where work belongs in a system.<br/>
Looking for a 6-month SWE internship starting early 2027.
</p>

---

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/glyph-currently-ink-dark.svg"><img src="assets/glyph-currently-ink-light.svg" width="18" alt=""></picture> Currently

- Teaching **[CS3219 Software Engineering Principles and Patterns](https://nusmods.com/courses/CS3219/software-engineering-principles-and-patterns)** at NUS as an academic tutor to a class of twenty, August to December 2026. One of my favourite modules taken in NUS, and the one that opened my eyes to how broad software engineering gets once distributed systems are involved. It is microservices based, so teams spend the semester making real decisions: where a service boundary goes, which database suits the access pattern, how everything gets deployed and stays up. My job is to help them think those through before they commit
- Taking **[DeepCS](https://github.com/Wnayar/deepcs)** (below) from Kubernetes locally onto GKE, then putting a Kafka adapter behind the event log interface it already has
- Building **[Recall](https://github.com/Wnayar/recall)** next, a search engine in Go, to understand indexing and retrieval by implementing them rather than reading about them

---

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/glyph-achievements-check-dark.svg"><img src="assets/glyph-achievements-check-light.svg" width="18" alt=""></picture> Achievements

- **1st place, Daytona HackSprint** by AI Builders at NUS (July 2026), for **Airlock** (below)
- **Certificate of Distinction**, Software Engineering focus area, NUS School of Computing
- **Three merged PRs** into [Automattic/mongoose](https://github.com/Automattic/mongoose) (27k stars) and [redis/node-redis](https://github.com/redis/node-redis) (17k stars), approved by both projects' lead maintainers. Gaps I found by reading the source rather than working off issue labels

---

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/glyph-work-ink-dark.svg"><img src="assets/glyph-work-ink-light.svg" width="18" alt=""></picture> Selected Work

### [DeepCS](https://github.com/Wnayar/deepcs) · Distributed · 6 Services

A CS interview question bank you work through alone, or live with a matched partner.

- Six independently deployable services in TypeScript and Fastify, with path filtered CI that builds and health checks each service's image on its own
- Real-time collaborative editing on WebSockets and Yjs, a CRDT, with edits carried between instances over Redis pub/sub. 250 sockets at p95 4ms on one machine
- A gateway I wrote rather than bought, verifying Firebase JWTs against Google's JWKS, with rate limiting and partner matching made atomic in Redis Lua
- One PostgreSQL instance with a schema and a role per service, and an integration test that asserts the database rejects cross-service queries
- An event pipeline on Redis Streams whose consumer acks only after commit, which is what turns at-least-once delivery into effectively exactly-once

*Built with:* &nbsp;`TypeScript` `Fastify` `PostgreSQL` `Redis` `Yjs` `Docker` `Kubernetes` `GitHub Actions`

### [Airlock](https://github.com/Wnayar/airlock) · 🏆 1st Place

1st place at the Daytona HackSprint. A safety gate that sits between an AI coding agent and every package it tries to install.

- Each install is detonated in an isolated sandbox before it touches the system, then read statically, matched against known malware, and reputation scored, with an LLM issuing the final verdict
- Enforced as a hook rather than a wrapper, so the agent cannot route around it
- Weekend team build; a teammate and I shaped the concept and system design

*Sponsors:* &nbsp;`Daytona` `Nosana` `Doubleword` `Oxylabs` `ai&`

### [Aqua Vitae](https://github.com/Wnayar/aqua-vitae) · [Live Site](https://www.aquavitaeparfums.com/)

Own venture. Sole engineer for a fragrance brand launching Dec 2026: storefront, backend and infrastructure.

- Backend on Supabase (PostgreSQL) and Vercel Functions: authentication, relational schema design, and caching
- React and TypeScript storefront with a Shopify hosted checkout, keeping payments and PCI scope off my stack
- CI/CD through Vercel, Cloudflare DNS and GitHub automation, with analytics supporting early testing across 100+ visitors

*Built with:* &nbsp;`TypeScript` `React` `PostgreSQL` `Supabase` `Vercel` `Cloudflare` `Shopify`

---

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/glyph-skills-ink-dark.svg"><img src="assets/glyph-skills-ink-light.svg" width="18" alt=""></picture> Technical Skills

**Languages**  
<img src="assets/skills-languages.svg" width="498" alt="JavaScript, TypeScript, Go, Python, Java, C, C++, Bash"/>

**Backend**  
<img src="assets/skills-backend.svg" width="498" alt="Node.js, Express, Flask, Fastify"/>

**Data**  
<img src="assets/skills-data.svg" width="498" alt="MongoDB, PostgreSQL, Redis, Supabase, SQLite, Firebase"/>

**Infra & Cloud**  
<img src="assets/skills-infra.svg" width="498" alt="Docker, Kubernetes, Google Cloud, AWS, Vercel, Cloudflare, GitHub Actions, Nginx, Linux"/>

**Frontend**  
<img src="assets/skills-frontend.svg" width="498" alt="React, Next.js, Tailwind CSS, Vite, HTML, CSS"/>

**Tools**  
<img src="assets/skills-tools.svg" width="498" alt="Git, GitHub, VS Code, Postman, Jest"/>
