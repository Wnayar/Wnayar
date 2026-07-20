<p align="center">
  <img src="banner.svg" width="100%" alt="William Nayar, backend and distributed systems"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/william-nayar/" title="LinkedIn"><img src="https://img.shields.io/badge/LinkedIn-070D14?style=for-the-badge&logo=linkedin&logoColor=F0B429"/></a>
  <a href="mailto:wnayar98@gmail.com" title="Email"><img src="https://img.shields.io/badge/Email-070D14?style=for-the-badge&logo=gmail&logoColor=F0B429"/></a>
</p>

<p align="center">
Final-year CS at NUS specialising in Software Engineering. I build backend systems and care about where work belongs in a system.<br/>
Looking for a 6-month SWE internship starting early 2027.
</p>

---

## Currently

- Building **Recall**, a search engine in Go, to understand indexing and retrieval by building them rather than reading about them
- Next: a real-time collaboration platform on TypeScript, Postgres and Redis

---

## Achievements

- **1st place, Daytona HackSprint** by AI Builders at NUS (July 2026), for **Airlock** (below)
- **Certificate of Distinction**, Software Engineering focus area, NUS School of Computing
- **Merged open source PRs** in [Automattic/mongoose](https://github.com/Automattic/mongoose) and [redis/node-redis](https://github.com/redis/node-redis), gaps I found by reading the source rather than working off issue labels

---

## Selected Work

### [Airlock](https://github.com/Wnayar/airlock) &nbsp;<sub>🏆 1st Place</sub>

1st place at the Daytona HackSprint. A safety gate that sits between an AI coding agent and every package it tries to install.

- Each install is detonated in an isolated sandbox before it touches the system, then read statically, matched against known malware, and reputation scored, with an LLM issuing the final verdict
- Enforced as a hook rather than a wrapper, so the agent cannot route around it
- Weekend team build; the concept and system design were mine

*Sponsors:* &nbsp;`Daytona` `Nosana` `Doubleword` `Oxylabs` `ai&`

### [Aqua Vitae](https://github.com/Wnayar/aqua-vitae) &nbsp;<sub><a href="https://www.aquavitaeparfums.com/"><img src="https://img.shields.io/badge/Live%20Site-070D14?style=flat&logoColor=F0B429" alt="Live Site"/></a></sub>

Own venture. Sole engineer for a fragrance brand launching Dec 2026: storefront, backend and infrastructure.

- Backend on Supabase (PostgreSQL) and Vercel Functions: authentication, relational schema design, and caching
- React and TypeScript storefront with a Shopify hosted checkout, keeping payments and PCI scope off my stack
- CI/CD through Vercel, Cloudflare DNS and GitHub automation, with analytics supporting early testing across 100+ visitors

*Built with:* &nbsp;`TypeScript` `React` `PostgreSQL` `Supabase` `Vercel` `Cloudflare` `Shopify`

### [PeerPrep](https://github.com/Wnayar/PeerPrep) &nbsp;<sub>Distributed · 6 Services</sub>

Question Service owned end to end within a distributed 6-service architecture.

- 15 RESTful endpoints with input validation and standardized error handling (400/404/409/500)
- Moved randomized question selection into MongoDB aggregation pipelines ($match, $sample) instead of the application layer
- 35 unit and integration tests with Jest and Supertest covering CRUD workflows and the pipelines

*Built with:* &nbsp;`Node.js` `Express` `TypeScript` `MongoDB` `Mongoose` `Jest` `Supertest`

### [Study-group platform](https://github.com/Wnayar/NUS-GroupMatch) &nbsp;<sub>NUS Orbital · Apollo 11</sub>

NUS Orbital, Apollo 11 Advanced. Full-stack MERN app for creating and discovering study groups, matched on live NUSMods course data.

- REST APIs with session-based auth (express-session, bcrypt) and MVC structure, with MongoDB schemas for users, groups and memberships
- Parsed nested timetable data (20 to 50+ entries per module) into structured formats with multi-criteria sorting and search

*Built with:* &nbsp;`MongoDB` `Express` `React` `Node.js`

---

## Technical Skills

| Category | Stack |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=js&theme=dark" title="JavaScript" width="38"/> <img src="https://skillicons.dev/icons?i=ts&theme=dark" title="TypeScript" width="38"/> <img src="https://skillicons.dev/icons?i=go&theme=dark" title="Go" width="38"/> <img src="https://skillicons.dev/icons?i=python&theme=dark" title="Python" width="38"/> <img src="https://skillicons.dev/icons?i=java&theme=dark" title="Java" width="38"/> <img src="https://skillicons.dev/icons?i=c&theme=dark" title="C" width="38"/> <img src="https://skillicons.dev/icons?i=cpp&theme=dark" title="C++" width="38"/> <img src="https://skillicons.dev/icons?i=bash&theme=dark" title="Bash" width="38"/> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs&theme=dark" title="Node.js" width="38"/> <img src="https://skillicons.dev/icons?i=express&theme=dark" title="Express" width="38"/> <img src="https://skillicons.dev/icons?i=flask&theme=dark" title="Flask" width="38"/> |
| **Data** | <img src="https://skillicons.dev/icons?i=mongodb&theme=dark" title="MongoDB" width="38"/> <img src="https://skillicons.dev/icons?i=postgresql&theme=dark" title="PostgreSQL" width="38"/> <img src="https://skillicons.dev/icons?i=redis&theme=dark" title="Redis" width="38"/> <img src="https://skillicons.dev/icons?i=supabase&theme=dark" title="Supabase" width="38"/> <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" title="SQLite" width="38"/> <img src="https://skillicons.dev/icons?i=firebase&theme=dark" title="Firebase" width="38"/> |
| **Infra & Cloud** | <img src="https://skillicons.dev/icons?i=docker&theme=dark" title="Docker" width="38"/> <img src="https://skillicons.dev/icons?i=gcp&theme=dark" title="Google Cloud" width="38"/> <img src="https://skillicons.dev/icons?i=aws&theme=dark" title="AWS" width="38"/> <img src="https://skillicons.dev/icons?i=vercel&theme=dark" title="Vercel" width="38"/> <img src="https://skillicons.dev/icons?i=cloudflare&theme=dark" title="Cloudflare" width="38"/> <img src="https://skillicons.dev/icons?i=githubactions&theme=dark" title="GitHub Actions" width="38"/> <img src="https://skillicons.dev/icons?i=nginx&theme=dark" title="Nginx" width="38"/> <img src="https://skillicons.dev/icons?i=linux&theme=dark" title="Linux" width="38"/> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react&theme=dark" title="React" width="38"/> <img src="https://skillicons.dev/icons?i=nextjs&theme=dark" title="Next.js" width="38"/> <img src="https://skillicons.dev/icons?i=tailwind&theme=dark" title="Tailwind CSS" width="38"/> <img src="https://skillicons.dev/icons?i=vite&theme=dark" title="Vite" width="38"/> |
| **Tools** | <img src="https://skillicons.dev/icons?i=git&theme=dark" title="Git" width="38"/> <img src="https://skillicons.dev/icons?i=github&theme=dark" title="GitHub" width="38"/> <img src="https://skillicons.dev/icons?i=vscode&theme=dark" title="VS Code" width="38"/> <img src="https://skillicons.dev/icons?i=postman&theme=dark" title="Postman" width="38"/> |
