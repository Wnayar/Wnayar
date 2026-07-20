<p align="center">
  <img src="banner.svg" width="900" alt="William Nayar, backend and distributed systems"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/william-nayar/" title="LinkedIn"><img src="https://img.shields.io/badge/LinkedIn-070D14?style=for-the-badge&logo=linkedin&logoColor=F0B429"/></a>
  <a href="mailto:wnayar98@gmail.com" title="Email"><img src="https://img.shields.io/badge/Email-070D14?style=for-the-badge&logo=gmail&logoColor=F0B429"/></a>
</p>

Final-year CS at NUS specialising in Software Engineering. I build backend systems and care about where work belongs in a system. Looking for a 6-month SWE internship starting early 2027.

## Currently

- Building **Recall**, a search engine in Go, to understand indexing and retrieval by building them rather than reading about them
- Next: a real-time collaboration platform on TypeScript, Postgres and Redis

## Achievements

- **1st place, Daytona HackSprint** by AI Builders at NUS (July 2026), for **Airlock** (below)
- **Certificate of Distinction**, Software Engineering focus area, NUS School of Computing
- **Merged open source PRs** in [Automattic/mongoose](https://github.com/Automattic/mongoose) and [redis/node-redis](https://github.com/redis/node-redis), gaps I found by reading the source rather than working off issue labels

## Selected Work

### Airlock

1st place at the Daytona HackSprint. A safety gate that sits between an AI coding agent and every package it tries to install.

- Each install is detonated in an isolated sandbox before it touches the system, then read statically, matched against known malware, and reputation scored, with an LLM issuing the final verdict
- Enforced as a hook rather than a wrapper, so the agent cannot route around it
- Weekend team build; the concept and system design were mine

`Daytona` `Nosana` `Doubleword` `Oxylabs` `ai&`

### Aqua Vitae &nbsp;[![Live](https://img.shields.io/badge/Live%20Site-070D14?style=flat&logoColor=F0B429)](https://www.aquavitaeparfums.com/)

Own venture. Sole engineer for a fragrance brand launching Dec 2026: storefront, backend and infrastructure.

- Backend on Supabase (PostgreSQL) and Vercel Functions: authentication, relational schema design, and caching
- React and TypeScript storefront with a Shopify hosted checkout, keeping payments and PCI scope off my stack
- CI/CD through Vercel, Cloudflare DNS and GitHub automation, with analytics supporting early testing across 100+ visitors

`TypeScript` `React` `PostgreSQL` `Supabase` `Vercel` `Cloudflare` `Shopify`

### PeerPrep

Question Service owned end to end within a distributed 6-service architecture.

- 15 RESTful endpoints with input validation and standardized error handling (400/404/409/500)
- Moved randomized question selection into MongoDB aggregation pipelines ($match, $sample) instead of the application layer
- 35 unit and integration tests with Jest and Supertest covering CRUD workflows and the pipelines

`Node.js` `Express` `TypeScript` `MongoDB` `Mongoose` `Jest` `Supertest`

### Study-group platform

NUS Orbital, Apollo 11 Advanced. Full-stack MERN app for creating and discovering study groups, matched on live NUSMods course data.

- REST APIs with session-based auth (express-session, bcrypt) and MVC structure, with MongoDB schemas for users, groups and memberships
- Parsed nested timetable data (20 to 50+ entries per module) into structured formats with multi-criteria sorting and search

`MongoDB` `Express` `React` `Node.js`

## Technical Skills

| | |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=js" title="JavaScript" width="42"/> <img src="https://skillicons.dev/icons?i=ts" title="TypeScript" width="42"/> <img src="https://skillicons.dev/icons?i=go" title="Go" width="42"/> <img src="https://skillicons.dev/icons?i=python" title="Python" width="42"/> <img src="https://skillicons.dev/icons?i=java" title="Java" width="42"/> <img src="https://skillicons.dev/icons?i=c" title="C" width="42"/> <img src="https://skillicons.dev/icons?i=cpp" title="C++" width="42"/> <img src="https://skillicons.dev/icons?i=bash" title="Bash" width="42"/> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs" title="Node.js" width="42"/> <img src="https://skillicons.dev/icons?i=express" title="Express" width="42"/> <img src="https://skillicons.dev/icons?i=flask" title="Flask" width="42"/> |
| **Data** | <img src="https://skillicons.dev/icons?i=mongodb" title="MongoDB" width="42"/> <img src="https://skillicons.dev/icons?i=postgresql" title="PostgreSQL" width="42"/> <img src="https://skillicons.dev/icons?i=redis" title="Redis" width="42"/> <img src="https://skillicons.dev/icons?i=supabase" title="Supabase" width="42"/> <img src="https://skillicons.dev/icons?i=sqlite" title="SQLite" width="42"/> <img src="https://skillicons.dev/icons?i=firebase" title="Firebase" width="42"/> |
| **Infra & Cloud** | <img src="https://skillicons.dev/icons?i=docker" title="Docker" width="42"/> <img src="https://skillicons.dev/icons?i=gcp" title="Google Cloud" width="42"/> <img src="https://skillicons.dev/icons?i=aws" title="AWS" width="42"/> <img src="https://skillicons.dev/icons?i=vercel" title="Vercel" width="42"/> <img src="https://skillicons.dev/icons?i=cloudflare" title="Cloudflare" width="42"/> <img src="https://skillicons.dev/icons?i=githubactions" title="GitHub Actions" width="42"/> <img src="https://skillicons.dev/icons?i=nginx" title="Nginx" width="42"/> <img src="https://skillicons.dev/icons?i=linux" title="Linux" width="42"/> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react" title="React" width="42"/> <img src="https://skillicons.dev/icons?i=nextjs" title="Next.js" width="42"/> <img src="https://skillicons.dev/icons?i=tailwind" title="Tailwind CSS" width="42"/> <img src="https://skillicons.dev/icons?i=vite" title="Vite" width="42"/> |
| **Tools** | <img src="https://skillicons.dev/icons?i=git" title="Git" width="42"/> <img src="https://skillicons.dev/icons?i=github" title="GitHub" width="42"/> <img src="https://skillicons.dev/icons?i=vscode" title="VS Code" width="42"/> <img src="https://skillicons.dev/icons?i=postman" title="Postman" width="42"/> |
