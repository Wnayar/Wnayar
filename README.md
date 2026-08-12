<p align="center">
  <img src="assets/banner-v3.svg" width="100%" alt="William Nayar, backend and distributed systems"/>
</p>

<p align="center">
  <b><a href="https://williamnayar.com/">Website</a></b>
  &nbsp;·&nbsp;
  <b><a href="https://williamnayar.com/resume">Resume</a></b>
  &nbsp;·&nbsp;
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
- Building **[Recall](https://github.com/Wnayar/recall)**, a search engine in Go, to understand indexing and retrieval by implementing them rather than reading about them

---

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/glyph-achievements-check-dark.svg"><img src="assets/glyph-achievements-check-light.svg" width="18" alt=""></picture> Achievements

- **1st place, Daytona HackSprint** by AI Builders at NUS (July 2026), for **Airlock** (below), a safety gate for AI agents
- **Certificate of Distinction**, Software Engineering, NUS School of Computing: 4.50 GPA across key Software Engineering modules
- **Three merged PRs** into [Automattic/mongoose](https://github.com/Automattic/mongoose) (27k stars) and [redis/node-redis](https://github.com/redis/node-redis) (17k stars), approved by both projects' lead maintainers. Gaps I found by reading the source rather than working off issue labels
- **Orbital Apollo 11 Certification**, NUS: advanced independent software development project
- **HackerRank Software Engineering Certification**: Problem Solving, SQL

---

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/glyph-work-ink-dark.svg"><img src="assets/glyph-work-ink-light.svg" width="18" alt=""></picture> Selected Work

### [DeepCS](https://github.com/Wnayar/deepcs) · Distributed · 6 Services

Solve CS interview questions solo or live with a matched partner.

- Built a distributed 6-service backend in TypeScript and Fastify, with path-filtered CI building and health-checking each service's image independently
- Built real-time collaborative editing on WebSockets and Yjs (CRDT), syncing edits across instances via Redis pub/sub, 250 sockets at p95 4 ms on one machine
- Built a custom API gateway with Firebase JWT verification against Google's JWKS, and made rate limiting and partner matching atomic with Redis Lua scripts
- Designed the data layer as one PostgreSQL instance with a schema and role per service, with an integration test asserting the database rejects cross-service queries
- Built an event pipeline on Redis Streams with a consumer that acks after commit, making at-least-once delivery effectively exactly-once
- In progress: running the stack on Kubernetes locally. Future: a GKE/GCP sprint, a Kafka adapter behind the event-log interface, and Drizzle over the pg layer

*Built with:* &nbsp;`TypeScript` `Fastify` `SQL` `Redis` `Docker` `Kubernetes`

### [Airlock](https://github.com/Wnayar/airlock) · 🏆 1st Place

1st place at the Daytona HackSprint. A safety gate that sits between an AI coding agent and every package it tries to install.

- Each install is detonated in an isolated sandbox before it touches the system, then read statically, matched against known malware, and reputation scored, with an LLM issuing the final verdict
- Enforced as a hook rather than a wrapper, so the agent cannot route around it
- Weekend team build; a teammate and I shaped the concept and system design

*Sponsors:* &nbsp;`Daytona` `Nosana` `Doubleword` `Oxylabs` `ai&`

### [Aqua Vitae](https://github.com/Wnayar/aqua-vitae) · [Live Site](https://www.aquavitaeparfums.com/)

Founder and developer. Perfumes that I make and sell myself.

- Designed a scalable frontend architecture using re-usable layouts, modals, and state management techniques, enabling ~70% code sharing and efficient creation of new features
- Implemented centralized cart state management using React Context and localStorage that allows real-time cart data sharing between different parts of the frontend (Navbar, product page, cart, overlays, etc.)
- Configured CI/CD and production deployment through Vercel, Cloudflare DNS, and GitHub automation

*Built with:* &nbsp;`React` `TypeScript` `PostgreSQL` `Vercel` `Cloudflare`

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
