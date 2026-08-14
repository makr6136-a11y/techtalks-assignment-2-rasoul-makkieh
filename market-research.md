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

**REST APIs — 6 / 6.** The API is the contract between the frontend and the backend; a full-stack developer spends most of their time either designing one, consuming one, or wiring a third-party service into the codebase.

**Relational databases and SQL — 6 / 6.** Every one of these applications has to persist state, and three listings (1, 4, 6) go further and ask for schema design and query optimization rather than just the ability to write a SELECT.

**JavaScript — 4 / 6.** It is the only language that runs in the browser; the frameworks layered on top of it differ from company to company, but the substrate does not.

**HTML and CSS — 4 / 6.** Whatever framework produces the markup, someone still has to make it render correctly and responsively.

**Authentication and security — 4 / 6.** These teams are handling user data, permissions and payments, and the requirement shows up at every level — from the mid-career role in listing 3 to the "junior" role in listing 5, which is expected to remediate vulnerabilities and patch dependencies.

The clearest signal in the table is what is *not* here: no framework appeared in more than 2 of 6 — not React, not Vue, not Next.js, not Laravel — while REST APIs and SQL both hit 6 of 6. Employers in this niche are hiring for fundamentals and treating the framework as something you pick up on the job.

### Secondary skills

**Frameworks and languages — no consensus, split by market.** React (2), PHP/Laravel (2), Next.js (1), Vue (1), TypeScript (1) and Node.js (1) all sit at the bottom of the table, and the split is geographic rather than random: PHP and Laravel appear only in the two on-site Beirut roles, while React, Next.js and TypeScript appear only in remote listings. Learning any one of them opens roughly a third of this sample and closes the rest, which is why none of them belongs in the essential tier.

**Infrastructure — concentrated in the remote listings, but not exclusively.** CI/CD (3) and Infrastructure as Code (2) appear only in listings 4, 5 and 6 — every remote role, no on-site role. Cloud (3) and Docker (2) are close but not absolute: listing 3 is on-site in Amman and still requires cloud environments with deployment, monitoring and backups, and listing 1 is on-site in Beirut and still requires Docker. So the pattern is real but has two exceptions, and cloud sits at 3/6 rather than 2/6 precisely because of listing 3. The honest version: remote employers expect you to deploy and operate what you build, and on-site employers usually don't — with enough leakage that "usually" is the right word.

**Practice and process — steady but shallow.** Git (3), documentation (3), testing (2), Agile or Scrum (2) and written English (2) each appear in a minority of listings, but they cut across both markets and every seniority level. Git in particular is under-counted: listings 5 and 6 both require CI/CD pipelines, which cannot function without version control, yet neither names Git anywhere in its requirements. The skill is assumed rather than requested — which means its true frequency is 5 of 6, and possibly 6.

**Nice-to-have only.** Some items never appear as a hard requirement anywhere. Listing 4 lists testing frameworks (Jest, Cypress, TDD), Docker and Kubernetes, serverless and AWS/Azure, and SEO as preferred; listing 1 lists BigQuery, Power BI and Go. These are differentiators between two otherwise equal candidates, not entry conditions.

**Zero mentions.** Java and Spring appear in 0 of 6 listings — worth stating explicitly, because they are a standard bootcamp track and carry no weight in this niche.

### What surprised me

**1. A "junior" role requiring four years of experience.** Listing 5 is titled *Junior Full Stack Engineer* and asks for a minimum of four years, plus AWS, Jenkins, Infrastructure as Code, secure coding and production triage. The title describes the salary band and the scope of authority, not the experience bar. Set against listing 2 — an intern role asking for basic-to-intermediate PHP — this sample has no genuine entry point in between: you are either an intern or you have four years. That gap is the single most important fact in this research for someone at my stage, because it means the intern route is not a fallback option, it is the route.

**2. Remote roles demand infrastructure skills that local roles mostly do not.** Every listing that requires CI/CD (4, 5, 6) and Infrastructure as Code (5, 6) is remote. Listings 1, 2 and 3 — all on-site in Beirut and Amman — ask for none of it, with two exceptions noted above: listing 1 wants Docker and listing 3 wants cloud deployment and monitoring. The likely reason is structural rather than technical: a remote hire has no one sitting next to them to push the release, so they must own the pipeline themselves. Practically, this means the local market will hire me to write features while the remote market will not hire me until I can also ship them.

**3. AI and LLM integration appeared repeatedly and is absent from the bootcamp reference list.** It is a hard requirement in listing 3 — LLM API integration, prompt configuration, structured outputs, and maintaining AI screening and matching workflows — and per [`sources.md`](sources.md) it also appeared in two listings excluded from this sample. One counted mention out of six is not a trend on its own; three sightings across a wider pool, in a category the reference curriculum does not mention at all, is at least worth watching. I would not restructure a roadmap around it, but I would expect it to be a scored requirement rather than a curiosity within a year.

**4. Non-technical requirements are more common than most individual technologies.** Written English is named outright in listing 1; communication is a listed skill in listing 5; documentation duties appear in listings 1 (runbooks, SOPs), 3 (technical and release documentation) and 5 (root-cause write-ups); code review participation appears in listings 2, 3 and 4. Some non-technical requirement is stated in 5 of 6 listings — more than React, Docker, TypeScript or any single framework in the table. For a Lebanon-based developer applying to remote roles, written English is not a soft skill on the side; it is the medium through which every other skill is evaluated.

### Skills currently missing from my profile

Current profile: SQL, Java/OOP, C++, HTML/CSS, Next.js in progress.

**Already covered.** SQL (6/6) and HTML/CSS (4/6) are both essential-tier and both already held — two of the five High rows are done. The caveat is depth: listings 1, 4 and 6 ask for schema design and query optimization, not just querying, so "I know SQL" needs to become "I have designed a schema and can explain why."

**Carries no weight in this niche.** Java and Spring scored 0/6. C++ does not appear in any of the six listings at all. These are real skills and they transfer — OOP, memory, algorithms — but no employer in this sample will hire on them. That is worth stating plainly, because it means my strongest existing language is not the one to build on.

**Critical gaps — essential tier, currently absent.**

- **REST APIs (6/6)** — the single highest-scoring requirement in the table and not yet in the profile. This is the first thing to fix.
- **JavaScript (4/6)** — Next.js in progress implies some exposure, but the listings ask for the language itself, and listing 2 specifies ES6+. Framework-first learning leaves this hollow.
- **Authentication and security (4/6)** — absent entirely, and required even of the "junior" role in listing 5.

**Assumed gaps — expected, rarely stated.**

- **Git (3/6 stated, 5–6/6 in practice)** — not in the profile, and not optional anywhere.
- **A backend language the market asks for** — the profile has no server-side language in demand here. PHP/Laravel opens the local market (listings 1, 2); Python opens the US remote market (listings 5, 6); Node.js appears once as an alternative. One of these is required; which one is a market decision, not a technical one.

**Remote-gated gaps — not needed to start, required to advance.** CI/CD (3/6), cloud (3/6), Docker (2/6), Infrastructure as Code (2/6), NoSQL (2/6), testing (2/6). None appear in the intern listing. All cluster in the roles paying remote wages.

**Low priority.** TypeScript (1/6), GraphQL (2/6), AI/LLM integration (1/6) — worth knowing they exist; not worth spending time on before the rows above are closed.

### Local vs. remote comparison

**Stack.** The two groups barely overlap. Local (1, 2, 3) runs on PHP — Laravel with Vue in listing 1, plain PHP with JavaScript in listing 2, unspecified full-stack with AI integration in listing 3. Remote (4, 5, 6) runs on the JavaScript/Python axis — React and Next.js with TypeScript in listing 4, Python with SQL in listing 5, React with either Python or Node.js in listing 6. PHP appears in zero remote listings; React appears in zero local listings. Only REST APIs and SQL are common to all six.

**Seniority.** Local spans the widest range: an intern role (2), a mid-career 3+ role (3), and a senior 5+ role (1). Remote has no true entry point — 5+ years (4), four years despite the "Junior" title (5), and Lead I (6). The only role in this sample I can apply to today is listing 2, and it is local.

**Expectations.** Local employers ask you to build: features, integrations, schemas, documentation. Remote employers ask you to build *and ship* — pipelines, deployments, monitoring, security remediation, Infrastructure as Code. Listing 5 makes the contrast sharpest: a role labelled junior that expects production triage, root-cause documentation and dependency patching.

**What this means for the roadmap.** The local market is the entry and the remote market is the destination, and they want different stacks — so the sequencing matters more than the total volume of learning. The shared foundation (REST APIs, SQL, JavaScript, Git, auth) serves both and should come first, because nothing else is portable between the two. The stack decision comes second and should follow whichever market I am actually applying to within the next six months. Infrastructure comes third: it is what converts a local-market profile into a remote-market one, and it is the reason the two salary bands in this sample look so different.

One honest tension: Next.js — the thing currently in progress — serves the remote market, which will not hire at my level for another few years, and does nothing for the local market, which will. That is worth resolving deliberately rather than by default.
