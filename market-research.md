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
| 6 | Mid-Level Full Stack Developer / UST Global | Chicago, IL, USA |Angular.js, Python or Java, FastAPI/Django/Flask, AWS (EC2, S3, RDS, IAM, Lambda, API Gateway), relational or NoSQL databases (MySQL, PostgreSQL, DynamoDB), RESTful APIs, Git, Agile, Jasmine/Karma, Pytest | Develop full-stack web applications; create Angular.js interfaces; build Python or Java server-side applications; deploy and scale applications on AWS; write documented and testable code; participate in code reviews; troubleshoot and maintain applications | 5+ years; Lead I – Software Engineering | Vue.js, serverless architecture with AWS Lambda, CI/CD practices and tools |

## 3. Pattern Analysis

### Frequency of requirements

Counts are based on required skills across the six listings. Where a technology appears only in a listing's responsibilities rather than its requirements list, it is still counted and noted. Nice-to-have mentions are excluded from the count and recorded in the notes column.

| Skill / Technology | Times Mentioned | Priority | Notes |
|--------------------|-----------------|----------|-------|
| Git / version control | 4 / 6 | High | Rows 2, 3, 4, 6. Not named in 1 or 5 |
| REST APIs | 6 / 6 | High | Every listing. Generic "APIs" in row 2 |
| Relational databases (SQL) | 6 / 6 | High | Generic "database" in rows 2 and 3 |
| NoSQL databases | 2 / 6 | Medium | Rows 4 (MongoDB) and 6 (DynamoDB as an option). Rows 1 and 5 are relational-only; rows 2 and 3 say only "databases" |
| JavaScript | 4 / 6 | High | Named in 1, 2 (ES6+), 4. Implied in 6 through Angular.js. Absent from 5, which is Python-only |
| HTML / CSS | 4 / 6 | High | Explicit in 2 and 4 (HTML5/CSS3); via Tailwind/Bootstrap in 1 and Angular UI libraries in 6. Not named in 3 or 5 |
| React | 1 / 6 | Low | Row 4 only |
| Next.js | 1 / 6 | Low | Row 4 only |
| Vue.js | 1 / 6 | Low | Row 1 only (Vue 2 and 3). The only local listing with a named frontend framework |
| TypeScript | 1 / 6 | Low | Row 4 only. No other listing names a typed JS layer |
| Node.js | 0 / 6 | None | Not mentioned in any analyzed listing |
| PHP / Laravel | 2 / 6 | Medium | Rows 1 and 2, both on-site in Beirut. Absent from all three remote listings |
| Python | 2 / 6 | Medium | Rows 5 and 6, both US remote. Absent from all three local listings |
| Java / Spring | 1 / 6 Java; 0 / 6 Spring | Low | Java is an alternative backend language in row 6; Spring is not mentioned |
| Authentication / security | 3 / 6 | Medium | Named in 3 (auth, permissions, data privacy) and 5 (secure coding, vulnerability remediation); a responsibility in 4 |
| Testing | 3 / 6 | Medium | Required in 2 (debug/test), 3 (UAT, regression) and 6 (Jasmine/Karma and Pytest). Jest, Cypress and TDD are nice-to-have in row 4 |
| Docker / containers | 1 / 6 | Low | Required in row 1. Nice-to-have in 4 (Docker, Kubernetes) |
| CI/CD | 2 / 6 | Medium | Required in rows 4 (GitHub/GitLab) and 5 (Jenkins). Preferred, not required, in row 6 |
| Cloud (AWS / GCP / Azure) | 3 / 6 | Medium | AWS named in 5 and 6; generic "cloud environments" in 3. Row 4 requires Vercel/Netlify but lists AWS/Azure as nice-to-have |
| Infrastructure as Code | 1 / 6 | Low | Row 5 only. No local listing mentions it |
| GraphQL | 1 / 6 | Low | Row 4 only, alongside REST rather than replacing it |
| Agile / Scrum | 3 / 6 | Medium | Rows 4 (Scrum/Kanban), 5 (Agile) and 6 (Agile). Row 3 implies a release process but never names a methodology |
| Documentation | 4 / 6 | High | Rows 1 (runbooks, SOPs), 3 (technical and release docs), 5 (root-cause write-ups) and 6 (documented code) |
| Written / spoken English | 2 / 6 | Medium | Row 1 names written English outright; row 5 lists communication as a required skill. Likely under-counted — assumed rather than stated elsewhere |
| AI / LLM integration | 1 / 6 | Low | Row 3 only, but deeply: LLM API integration, prompt configuration, structured outputs, AI screening workflows. Also present in two excluded listings |


Priority is assigned by raw frequency only: 4+ = High, 2–3 = Medium, 1 = Low. Relevance to remote roles specifically is discussed in the analysis below.

### Essential skills

**REST APIs — 6 / 6.** The API is the contract between the frontend and the backend; a full-stack developer spends most of their time either designing one, consuming one, or wiring a third-party service into the codebase.

**Relational databases and SQL — 6 / 6.** Every one of these applications has to persist state, and three listings (1, 4, 6) go further and ask for schema design and query optimization rather than just the ability to write a SELECT.

**JavaScript — 4 / 6.** It is the only language that runs in the browser; the frameworks layered on top of it differ from company to company, but the substrate does not.

**HTML and CSS — 4 / 6.** Whatever framework produces the markup, someone still has to make it render correctly and responsively.

**Git and documentation — 4 / 6 each.** Employers repeatedly ask candidates to work through shared version-control and review processes and to leave behind readable technical evidence, from runbooks and release notes to documented code and root-cause reports.

The clearest signal in the table is what is *not* here: no framework appeared in more than 2 of 6 — not React, not Vue, not Next.js, not Laravel — while REST APIs and SQL both hit 6 of 6. Employers in this niche are hiring for fundamentals and treating the framework as something you pick up on the job.

### Secondary skills

**Frameworks and languages — no consensus, split by market.** PHP/Laravel appears in two listings, while React, Next.js, Vue, TypeScript, Angular and Java appear in only one each. PHP is concentrated in the two Beirut roles; React, Next.js and TypeScript appear in the remote Visualis Media listing; Angular and Java appear in the Chicago UST listing. No framework belongs in the essential tier.

**Infrastructure — concentrated outside the entry-level local role.** CI/CD is required in listings 4 and 5 and preferred in 6; Infrastructure as Code is required only in 5. Cloud appears in listings 3, 5 and 6, while Docker is required only in listing 1 and preferred in 4. The reliable conclusion is that deployment and operations skills become more important in experienced and non-local roles, not that every remote role asks for the same toolset.

**Practice and process — broadly useful.** Git (4), documentation (4), testing (3), Agile or Scrum (3) and written English or communication (2) cut across markets and seniority levels. Listing 6 strengthens this pattern by explicitly requiring Git, Agile work, documented code, code review and named testing frameworks.

**Nice-to-have only.** Listing 4 lists Jest, Cypress, TDD, Docker, Kubernetes, serverless, AWS/Azure and SEO as preferred; listing 6 lists Vue, serverless architecture and CI/CD as preferred; listing 1 lists BigQuery, Power BI and Go. These are differentiators rather than entry conditions for those roles.

**Zero mentions.** Spring, Node.js and C++ appear in 0 of 6 listings. Java appears once as an alternative backend language in listing 6.

### What surprised me

**1. A "junior" role requiring four years of experience.** Listing 5 is titled *Junior Full Stack Engineer* and asks for a minimum of four years, plus AWS, Jenkins, Infrastructure as Code, secure coding and production triage. The title describes the salary band and the scope of authority, not the experience bar. Set against listing 2 — an intern role asking for basic-to-intermediate PHP — this sample has no genuine entry point in between: you are either an intern or you have four years. That gap is the single most important fact in this research for someone at my stage, because it means the intern route is not a fallback option, it is the route.

**2. Experienced and non-local roles demand more deployment knowledge.** CI/CD is required in listings 4 and 5 and preferred in 6; cloud appears in listings 3, 5 and 6; Infrastructure as Code appears in listing 5. The intern role asks for none of these. Practically, this means I should first become employable through application fundamentals, then add deployment and operations skills as I move toward more experienced or remote roles.

**3. AI and LLM integration appeared repeatedly and is absent from the bootcamp reference list.** It is a hard requirement in listing 3 — LLM API integration, prompt configuration, structured outputs, and maintaining AI screening and matching workflows — and per [`sources.md`](sources.md) it also appeared in two listings excluded from this sample. One counted mention out of six is not a trend on its own; three sightings across a wider pool, in a category the reference curriculum does not mention at all, is at least worth watching. I would not restructure a roadmap around it, but I would expect it to be a scored requirement rather than a curiosity within a year.

**4. Non-technical requirements are more common than most individual technologies.** Written English is named outright in listing 1; communication is required in listing 5; documentation duties appear in listings 1, 3, 5 and 6; code review participation appears in listings 2, 3, 4 and 6. Some non-technical requirement is stated in all six listings — more than any single framework in the table.

### Skills currently missing from my profile

Current profile: SQL, Java/OOP, C++, HTML/CSS, Next.js in progress.

**Already covered.** SQL (6/6) and HTML/CSS (4/6) are both essential-tier and both already held — two of the five High rows are done. The caveat is depth: listings 1, 4 and 6 ask for schema design and query optimization, not just querying, so "I know SQL" needs to become "I have designed a schema and can explain why."

**Limited direct weight in this niche.** Java appears once as an alternative backend language in listing 6, while Spring and C++ appear nowhere. These skills still transfer through OOP, algorithms and problem solving, but Java is not the dominant language in this sample.

**Critical gaps — essential tier, currently absent.**

- **REST APIs (6/6)** — the single highest-scoring requirement in the table and not yet in the profile. This is the first thing to fix.
- **JavaScript (4/6)** — Next.js in progress implies some exposure, but the listings ask for the language itself, and listing 2 specifies ES6+. Framework-first learning leaves this hollow.
- **Authentication and security (3/6)** — absent entirely, and required even of the "junior" role in listing 5.

**Assumed gaps — expected, rarely stated.**

- **Git (4/6)** — not in the profile, and central to collaboration, review and deployment workflows.
- **A backend language the market asks for** — PHP/Laravel opens the local market (listings 1, 2), while Python appears in the two US-based listings (5, 6). Java is accepted as an alternative in listing 6. One of these paths is required; which one is a market decision, not only a technical preference.

**Advancement gaps — not needed to start, useful for experienced roles.** CI/CD (2/6 required, plus one preferred), cloud (3/6), Docker (1/6 required), Infrastructure as Code (1/6), NoSQL (2/6) and testing (3/6). None appear as infrastructure requirements in the intern listing.

**Low priority.** TypeScript (1/6), GraphQL (1/6) and AI/LLM integration (1/6) are worth monitoring but not worth prioritizing before the higher-frequency requirements. GraphQL appears only in listing 4 and alongside REST rather than replacing it.

### Local vs. remote comparison

**Stack.** The two Beirut listings use PHP, with Laravel/Vue in listing 1 and plain PHP/JavaScript in listing 2. The Amman role does not name a framework. The remote listings use React/Next.js/TypeScript in listing 4 and Python/SQL in listing 5, while the Chicago listing uses Angular with Python or Java. Framework choices vary, while REST APIs and database work remain common across all six.

**Seniority.** Local spans an intern role (2), a mid-career 3+ role (3), and a senior 5+ role (1). The two remote listings require 5+ years (4) and four years despite the "Junior" title (5); the Chicago UST listing also requires 5+ years (6). The only role in this sample I can apply to today is listing 2, and it is local.

**Expectations.** Local employers ask you to build: features, integrations, schemas, documentation. Remote employers ask you to build *and ship* — pipelines, deployments, monitoring, security remediation, Infrastructure as Code. Listing 5 makes the contrast sharpest: a role labelled junior that expects production triage, root-cause documentation and dependency patching.

**What this means for the roadmap.** The local market is the entry and the remote market is the destination, and they want different stacks — so the sequencing matters more than the total volume of learning. The shared foundation (REST APIs, SQL, JavaScript, Git, auth) serves both and should come first, because nothing else is portable between the two. The stack decision comes second and should follow whichever market I am actually applying to within the next six months. Infrastructure comes third: it is what converts a local-market profile into a remote-market one, and it is the reason the two salary bands in this sample look so different.

One honest tension: Next.js — the thing currently in progress — serves the remote market, which will not hire at my level for another few years, and does nothing for the local market, which will. That is worth resolving deliberately rather than by default.
