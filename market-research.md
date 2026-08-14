# Market Research

Target niche: **Full-Stack Developer**. Six listings analyzed. Links and exclusions are documented in [`sources.md`](sources.md).

## 2. Job Listing Research

| # | Role / Company | Location | Core Skills (required) | Responsibilities | Experience | Nice-to-Have |
|---|----------------|----------|------------------------|------------------|------------|--------------|
| 1 | Full-Stack Engineer / Infoquest | Beirut, Lebanon (on-site) | PHP, Laravel, PostgreSQL (MySQL accepted), Vue 2 & 3, JavaScript, Tailwind CSS, Bootstrap, jQuery, REST APIs, third-party integrations, Docker, Linux, Nginx, OOP, MVC, SOLID, database schema design, documentation, written English | Build and maintain custom CRM features; develop Vue frontend and Laravel backend; design REST APIs and integrations (Zoom, Google Workspace, Teams); maintain BigQuery/Power BI reporting and dashboards; write runbooks and SOPs | 5+ years | BigQuery or cloud data warehouse, Power BI, data engineering (pipelines, data modelling, SQL optimization), SaaS/CRM/billing/compliance systems, expert-network industry experience, Go |
| 2 | Developer Intern / Presentail | Beirut, Lebanon (on-site) |PHP (basic–intermediate), JavaScript (ES6+), HTML, CSS, client-server architecture, APIs, databases, Git |Develop and maintain web apps in PHP and JavaScript; support backend APIs, server-side logic and databases; build frontend features and UI behavior; debug, test and optimize code; participate in code reviews | Intern, basic to intermediate |None stated (ES6+ preferred) |
| 3 | Full-Stack Software Engineer – SaaS & AI / VirtuStaff | Amman, Jordan (on-site) |Full-stack development (frontend, backend, database, architecture), REST and third-party API integration, AI/LLM API integration, prompt configuration and structured outputs, Git with branching and release documentation, cloud environments (deployment, monitoring, backups), authentication and permissions, data security and privacy, UAT and regression testing, code reviews, technical documentation |Take structured handover of an existing codebase from a third-party team; develop, test and release platform features; fix frontend, backend, API, integration and database defects; maintain AI candidate-screening and matching workflows; build CRM, email, analytics, payment and notification integrations; support cloud deployments and monitoring | 3+ years, mid career |None stated |
| 4 | Senior Full Stack Developer / Visualis Media | Lebanon (remote) |Next.js, React, TypeScript, JavaScript, HTML5, CSS3, SQL and NoSQL (PostgreSQL, MongoDB), CMS frameworks (Contentful, Strapi), Vercel/Netlify deployment, Git with branching and code review, CI/CD (GitHub, GitLab), REST APIs, GraphQL, Agile/Scrum/Kanban |Design, develop and maintain web applications in Next.js and React; manage MongoDB and NoSQL schema design; implement and optimize deployment workflows on Vercel/Netlify; define Git branching strategies, code review guidelines and CI/CD workflows; optimize for performance, security and scalability; debug and troubleshoot | 5+ years |Serverless architecture and cloud (AWS, Azure), testing frameworks (Jest, Cypress) and TDD, SEO best practices, containerization (Docker, Kubernetes) |
| 5 | Junior Full Stack Engineer / Index Analytics | Windsor Mill, MD, USA (remote) |SQL, Python, RESTful APIs, relational databases (PostgreSQL/Aurora), AWS (S3, Secrets Manager, SSM), CI/CD (Jenkins), Infrastructure as Code, monitoring and troubleshooting (CloudWatch, Splunk), secure coding, Agile, communication |Support full-stack development across frontend, backend and database layers; participate in the full SDLC with mentorship; develop and consume REST APIs; deploy and support applications in AWS; contribute to IaC templates promoted through CI/CD; triage production issues and document root cause; remediate security vulnerabilities and patch dependencies | Titled "Junior" but requires 4 years | DevSecOps practices (preferred), prior experience with CMS or other government agencies|
| 6 | Full Stack Developer / UST | Chicago, IL, USA (remote) |React, Redux/Context API, modern CSS frameworks, Python (FastAPI, Django, Flask) or Node.js (Express, NestJS), microservices, REST and GraphQL APIs, API security (injection, broken object-level authorization), AWS, containerization, Infrastructure as Code, CI/CD, relational databases (PostgreSQL, MySQL), NoSQL (DynamoDB, MongoDB), schema design and query optimization | Build modular responsive UIs in React; design and scale backend services and microservices; architect and secure REST/GraphQL APIs; deploy and manage components in AWS containerized environments; own deployment workflows through IaC and automated CI/CD gates; design schemas and write optimized queries across SQL and NoSQL| Lead I – Software Engineering |Not stated (listing truncated) |

## 3. Pattern Analysis

### Frequency of requirements

Counts are based on required skills across the six listings. Where a technology appears only in a listing's responsibilities rather than its requirements list, it is still counted and noted. Nice-to-have mentions are excluded from the count and recorded in the notes column.

| Skill / Technology | Times Mentioned | Priority | Notes |
|--------------------|-----------------|----------|-------|
| Git / version control | 3 / 6 | Medium | Rows 2, 3, 4. Not named in 1, 5, 6 |
| REST APIs | 6 / 6 | High | Every listing. Generic "APIs" in row 2 |
| Relational databases (SQL) | 6 / 6 | High | Generic "database" in rows 2 and 3 |
| NoSQL databases | 2 / 6 | Medium | Rows 4 (MongoDB) and 6 (DynamoDB, MongoDB) — both remote. Rows 1 and 5 are relational-only; rows 2 and 3 say only "databases" |
| JavaScript | 4 / 6 | High | Named in 1, 2 (ES6+), 4. Implied in 6 via React/Redux. Absent from 5, which is Python-only |
| HTML / CSS | 4 / 6 | High | Explicit in 2 and 4 (HTML5/CSS3); via Tailwind/Bootstrap in 1 and "modern CSS frameworks" in 6. Not named in 3 or 5 |
| React | 2 / 6 | Medium | Only in the two remote listings (4, 6) |
| Next.js | 1 / 6 | Low | Row 4 only. Row 6 wants React with no framework named |
| Vue.js | 1 / 6 | Low | Row 1 only (Vue 2 and 3). The only local listing with a named frontend framework |
| TypeScript | 1 / 6 | Low | Row 4 only. No other listing names a typed JS layer |
| Node.js | 1 / 6 | Low | Row 6 only, and offered as an alternative to Python — not mandatory |
| PHP / Laravel | 2 / 6 | Medium | Rows 1 and 2, both on-site in Beirut. Absent from all three remote listings |
| Python | 2 / 6 | Medium | Rows 5 and 6, both US remote. Absent from all three local listings |
| Java / Spring | 0 / 6 | None | Not mentioned in any listing, despite being standard in bootcamp curricula |
| Authentication / security | 4 / 6 | High | Named as a skill in 3 (auth, permissions, data privacy), 5 (secure coding, vulnerability remediation), 6 (API security, injection, BOLA); as a responsibility in 4 |
| Testing | 2 / 6 | Medium | Required in 2 (debug/test) and 3 (UAT, regression). Frameworks (Jest, Cypress, TDD) appear only as nice-to-have in row 4 — no listing requires a named framework |
| Docker / containers | 2 / 6 | Medium | Rows 1 (Docker) and 6 (containerization). Nice-to-have in 4 (Docker, Kubernetes) |
| CI/CD | 3 / 6 | Medium | Rows 4 (GitHub/GitLab), 5 (Jenkins), 6 (automated gates) — all three remote. Absent from all three on-site |
| Cloud (AWS / GCP / Azure) | 3 / 6 | Medium | AWS named in 5 and 6; generic "cloud environments" in 3. Row 4 requires Vercel/Netlify but lists AWS/Azure as nice-to-have |
| Infrastructure as Code | 2 / 6 | Medium | Rows 5 and 6 only — the two US remote listings. No local listing mentions it |
| GraphQL | 2 / 6 | Medium | Rows 4 and 6, both remote, and both alongside REST rather than replacing it |
| Agile / Scrum | 2 / 6 | Medium | Rows 4 (Scrum/Kanban) and 5 (Agile). Row 3 implies a release process but never names a methodology |
| Documentation | 3 / 6 | Medium | Rows 1 (runbooks, SOPs), 3 (technical and release docs), 5 (root-cause write-ups). Spans local and remote, junior and senior |
| Written / spoken English | 2 / 6 | Medium | Row 1 names written English outright; row 5 lists communication as a required skill. Likely under-counted — assumed rather than stated elsewhere |
| AI / LLM integration | 1 / 6 | Low | Row 3 only, but deeply: LLM API integration, prompt configuration, structured outputs, AI screening workflows. Also present in two excluded listings |


Priority is assigned by raw frequency only: 4+ = High, 2–3 = Medium, 1 = Low. Relevance to remote roles specifically is discussed in the analysis below.

### Essential skills

Which items scored highest, and why they are non-negotiable for this niche.

### Secondary skills

Which items appeared in a minority of listings, or only as nice-to-have.

### What surprised me

Three observations are already supported by your evidence — expand each one with the specific listings that back it:

1. **A "Junior" role requiring four years of experience.** Listing 5 is titled *Junior Full Stack Engineer* and requires a minimum of four years. What does this say about the entry-level market?
2. **Remote roles demand infrastructure skills that local roles do not.** Compare the required stacks of listings 5 and 6 against listings 1, 2, and 3. Which category asks for AWS, CI/CD, and Infrastructure as Code?
3. **AI integration appeared repeatedly and is absent from the bootcamp reference list.** It appeared in listing 3 and in two excluded listings. Is this noise, or a trend?

Also consider: non-technical requirements. Written English, documentation habits, and communication appear explicitly in several listings. How often, and where?

### Skills currently missing from my profile

Compare the frequency table against what you already have (SQL, Java/OOP, C++, HTML/CSS, Next.js in progress). List the gaps — these become the input to [`roadmap.md`](roadmap.md).

### Local vs. remote comparison

Listings 1, 2, and 3 are on-site in Lebanon and Jordan. Listings 4, 5, and 6 are remote. Compare the two groups: stack, seniority, and expectations. This comparison is the strongest evidence you have for the roadmap.
